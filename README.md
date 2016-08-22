## What is it?
Google's library for [In App Billing](http://developer.android.com/google/play/billing/index.html).

## Why here?
Because of Google hasn't published it to any repository yet.

## Where published?
[Here](https://bintray.com/alexeydanilov/maven/in-app-billing)

## How to use?
Modify `build.gradle`:
```
repositories {
    maven { url 'https://dl.bintray.com/alexeydanilov/maven' }
}

dependencies {
    compile 'com.danikula.iab:in-app-billing:1.5@aar'
}
```

## Thanks
Thanks for [bintray-release](https://github.com/novoda/bintray-release) for easy publishing.

## Licence

    Copyright 2016 Alexey Danilov

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.LICENSE