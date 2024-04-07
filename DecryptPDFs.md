### Decrypt password encrypted pdfs.
The below commands decrypt pdf files with password encryption. 
**$ pdftk encrypted.pdf input_pw PROMPT output decrypted.pdf**  
**$ qpdf encrypted.pdf --decrypt --remove-restrictions --password=your-secret-password decrypted.pdf**
