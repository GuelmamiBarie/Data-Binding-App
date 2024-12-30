The first issue is what about large applications with hundreds of views and layouts?
Modern mobiles nowadays have a refresh rate 60Hz per one second, so Android system will create our
layout with all its views every 16.6, six, seven milliseconds for a refresh rate 60Hz.
The second issue, what about mobiles with 90Hz, 120Hz, 144Hz and more?
So Android system will create our layout with all its views with less time.
And this could lead to memory leaks and missing views.
The solution is to use the data binding library.
Android Jetpack is a set of libraries designed to help developers follow best practices and create code
quickly and simply.
The data binding library is one of these libraries.
So the data binding library is a support library that allows you to bind UI components in your layout
to data sources in your app using a declarative format rather than programmatically data binding is
the process of integrating views in an XML layout with data objects.
The data binding library is responsible for generating the classes required for this procedure.
Using data binding and binding object will be created.
