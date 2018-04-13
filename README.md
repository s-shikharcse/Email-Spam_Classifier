# Email-Spam_Classifier

We all face the problem of spams in our inboxes. Let’s build a spam classifier program in python which can tell whether a given message is spam or not! We can do this by using a simple, yet powerful theorem from probability theory called Baye’s Theorem. It is mathematically expressed as




![1 82tln2qziioehv2em4doiq](https://user-images.githubusercontent.com/30600908/38755477-78fd2634-3f83-11e8-8f89-a3f574a010b9.png)






We have a message m = (w1, w2, . . . . , wn), where (w1, w2, . . . . , wn) is a set of unique words contained in the message. We need to find



![1 fngyu6bsb_qw82aldd2e9q](https://user-images.githubusercontent.com/30600908/38755548-c43b08aa-3f83-11e8-8822-578370b7ab0a.png)




If we assume that occurrence of a word are independent of all other words, we can simplify the above expression to



![3](https://user-images.githubusercontent.com/30600908/38755609-0335c9c8-3f84-11e8-866c-f92b40c4ef32.png)




In order to classify we have to determine which is greater




This project classifies the email as spam or not based on the scanning of the email body. The program compares the string tokens with that of already stored spam-keywords and if it finds the one then reports the mail as spam otherwise not.

If classified as spam will place in spam folder or give label of spam. If not spam will show in inbox as normal inbox message.

Download Dataset from the given link:

     https://drive.google.com/open?id=1bhx83hB8aS8EnQepSjzD_OoRnK-ArJiQ
