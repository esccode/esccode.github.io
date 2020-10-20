---
layout: post
title: Google Apps Script
tags: 
- google apps script
---
[Google Apps Script](https://developers.google.com/apps-script)

Increase the power of your favorite Google apps — like Calendar, Docs, Drive, Gmail, Sheets, and Slides.
Apps Script lets you d[o more with Google](https://developers.google.com/apps-script/guides/services), all on a [modern JavaScript platform](https://developers.google.com/apps-script/guides/v8-runtime) in the cloud. Build [solutions](https://developers.google.com/gsuite/solutions) to boost your collaboration and productivity.

Below is just about everything you'll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

## Example

```
//https://www.tiny.cloud/

function onOpen() {
  var ui = SpreadsheetApp.getUi();
  ui.createMenu('Custom Menu')
      .addItem('Send Email', 'sendMail')
      .addToUi();
}

function sendMail() {
  
  var first = 0;
  var last = 1;
  var email = 2;
  var phone = 3;
  
  
  var emailTemp = HtmlService.createTemplateFromFile('email');
  var ws = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('contact');
  var wsSettings = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('settings');
  
  var name = wsSettings.getRange("B2").getValue();
  var subject = wsSettings.getRange("B1").getValue();
  
  
  var data = ws.getRange('B2:G'+ ws.getLastRow()).getValues();
  data = data.filter(function(r){ return r[5] == true});
  
  //Logger.log(data);
  data.forEach(function(row){
        emailTemp.fn = row[first];
        emailTemp.ln = row[last];
        emailTemp.phone = row[phone];
        var htmlMessage = emailTemp.evaluate().getContent();
    GmailApp.sendEmail(row[email],
                       "Important Message",
                       "Your email doesn't support HTML. ",
                       {name:"Email App", htmlBody: htmlMessage}
                      )
  });
 }

```


