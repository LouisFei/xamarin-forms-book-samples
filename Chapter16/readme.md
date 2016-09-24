Data binding
Events and event handlers are a vital part of the interactive interface of Xamarin.Forms, but often event handlers perform very rudimentary jobs. They transfer values between properties of different objects and in some cases simply update a Label to show the new value of a view.
�¼����¼�������Xamarin.Forms������һ����Ҫ��ɲ��֣�Ȼ��ͨ���¼�ֻ����ǳ������Ĺ����������ڲ�ͬ��������Լ䴫��ֵ��������һ����ͼ�м򵥵ظ���һ����ǩ����ʾ�µ�ֵ��


You can automate such connections between properties of two objects with a powerful feature of Xamarin.Forms called data binding. Under the covers, a data binding installs event handlers and handles the transfer of values from one property to another so that you don��t have to. In most cases you define these data bindings in the XAML file, so there��s no code (or very little code) involved. The use of data bindings helps reduce the number of ��moving parts�� in the application.
ʹ��Xamarin.Forms�б���Ϊ"data binding"�ĸ߼����ԣ�������Զ�����������������ԡ�����

Data bindings also play a crucial role in the Model-View-ViewModel (MVVM) application architec-ture. As you��ll see in Chapter 18, ��MVVM,�� data bindings provide the link between the View (the user interface often implemented in XAML) and the underlying data of the ViewModel and Model. This means that the connections between the user interface and underlying data can be represented in XAML along with the user interface.
���ݰ���MVVM�ܹ��а�����Ҫ��ɫ��

