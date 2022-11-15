//Apex Message Snipet
 Messaging.SingleEmailMessage mail = New Messaging.SingleEmailMessage();
        String[] toAddress= New String[]{'Komalbhat540@gmail.com'};
            mail.setToAddresses(toAddress);
        mail.setSubject('Batch Job Completed');
        mail.setPlainTextBody('Hey');
        Messaging.sendEmail(New Messaging.SingleEmailMessage[]{mail});
        
