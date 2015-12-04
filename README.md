# Floaties 
Floaties is a simple library to create floating windows.

Play Store Demo: 

### Why use it?
Floaties is a library and **not** a demo application. You can create your own Floating Window using two simple lines:

```
Floaty floaty = Floaty.createInstance(context, head, body, NOTIFICATION_ID, notification);
floaty.startService();
```
`head` and `body` are both of type `View` which means, you could use anything as the head or the body of the floating window.

### How to use it?
You can include **Floaties** in your project using the following gradle dependency:

```
dependencies {
    compile 'com.bezyapps.floatieslibrary:floaties:1.0.1'
}
```

If you plan on targeting Android M or above, please see [this](https://github.com/ericbhatti/floaties/blob/master/FloatiesDemo/app/src/main/java/com/bezyapps/floatiesdemo/MainActivity.java) on how permission is to be requested.





