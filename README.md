# nihaopay-opencart3

opencart 2.0.3.1

 If you have any other questions，You may contact:liang.qin@aurfy.com 
 
 Installation instructions：
 
(一)

1.Upload system background  …….ocmod.zip；

2.In the system management background(Extensions->Installer->Upload)

3.In the system management background(Extensions->Extensions->Choose the extension type(Payments))

Add Payment Method

The input:Token,Transaction Server,Geo Zone,Total,Order Status,Status,Sort Order

Token              —- NihaoPay system generated by the Token

Transaction Server —- Live(The production environment),Test(The test environment)

Geo Zone	          —- Default All zones

Total		            —- The checkout total the order must reach before this payment method becomes active(Don't fill in, the default is                         empty)

Order Status       —- Pay after the completion of the order status

Status             —- Whether to enable

Sort Order         —- Don't fill in, the default is empty
 
 
 
(二)


Copy the content of upload folder into your OpenCart root folder.

This module don't replace any OpenCart's core files.



Pay attention to：

1.Check the mail service configuration(Send email make mistakes or infinite wait)
 
2.Please do not arbitrarily modify the program，There may be off single
 
3.Interface is installed，Such as additional add other components or modules，Please test for a normal trading data again

4.After changes the system default currency，Please refresh rate

(三)

Website to install document：http://docs.opencart.com/extension/modifications/


Instructions
================

NihaoPay plug-in，Support:Credit Card payment,UnionPay Online payment,AliPay online payment,WechatPay online payment



Note
==================

 If you have any other questions，You may contact:liang.qin@aurfy.com 
