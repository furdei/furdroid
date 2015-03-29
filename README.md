# furdroid

**Furdroid** is a set of open source Android components. It will help you to bring material design
to any device, extending a functionality of Google's Support Library.

We care about the size of your application. That's why each component comes withing
it's own separate module so that you can use it without wasting precious kilobytes
on components you don't need. Each module is published at Maven Central Repository.
There is no need to download anything. You just need to write a couple of lines
to include it in your awesome app!

### Material Floating Menu

**Furdroid** introduces a [FloatingMenu](https://github.com/furdei/furdroid-floatingmenu)
component: trendy widget to help you implement
material-styled menu. It's totally customizable and extendable. It can be of any shape,
open and close using any animation. And it is designed to be easily styled with your custom theme.
**Furdroid** comes with 3d party implementation of RippleDrawable in Java, so that you can use it
on any device regardless of it's API version.

### Navigation Toolbar

[NavigationToolbar](https://github.com/furdei/furdroid-navigationtoolbar) is another useful
material component. It appears on the left side of the screen where navigation components
usually expected. You can implement awesome navigation if combine NavigationToolbar with a
material NavigationDrawer.

### Secure Storage

[Furdroid-security](https://github.com/furdei/furdroid-security) is helpful if you want to implement
a secure Android storage. **Furdroid** provides you with a set of components to work with encrypted
database and file storage. You still work with SQLite database but it's content is encrypted. You
can configure which tables and which columns should be encrypted. **Furdroid** will also help you to
generate key and store it in a secure manner.

### Furdroid Components

[Furdroid-components](https://github.com/furdei/furdroid-components) is a set of light-weight reusable
Android components, such as TintedDrawable support for any API version, PartialLoadingAdapter,
FullCursorAdapter and visual widgets to work with FullCursorAdapter.

## Before you start

Before you start using **furdroid** please make sure you have Android jars 'android:android' and
'com.android.support' in your local Maven repository. If you don't please visit
[maven-android-sdk-deployer](https://github.com/simpligility/maven-android-sdk-deployer)
project and follow the instruction.

Copyright (c) 2015 *furdei.systems* [www.furdei.systems](http://www.furdei.systems)
