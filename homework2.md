# Native, Hybrid and Web App
## Classification of the app
They can be divided into following three kinds.
![Brief classification](https://upload-images.jianshu.io/upload_images/1668945-eebff27c68f3e4db.png?imageMogr2/auto-orient/)
* native app
* hybrid app
* web app
## Definition of each type of app
### Native app
　　Based on the local operating systems of smart phones, such as iOS, Android and WP, and using native programs to write and run third-party applications, the commonly developed languages are Java, C++, etc.The specific expression on the use is that the graph on the desktop is basically a native app.
### Web app
　　Web-based systems and applications, running on the web and browsers, are currently developed using the h5 standard.<br>
The specific performance on use is that when the mobile browser is clicked to enter, there will be some small ICONS of the app. After clicking, the page loaded in the browser is the same as the page opened after you directly download an app. These little ICONS represent the web app.
### Hybrid app
　　As the name implies, it is a mixture of native app and web app.A browser is built in the native app, and the appropriate functional pages are rendered in the form of web pages.For example, some marketing pages of jd.com, some news pages of today's headlines, and content pages of tencent news of WeChat.
## Advantages and disadvantages of each one
### Native app
#### Advantages
* Access to all the functions on your phone (GPS, camera, etc.)
* Better speed, performance and user experience
* Support offline work (because it is running on the device, not the web)
* Download in the app store and easily find app ICONS on the home screen.
#### Disadvantages
* High development costs.
* Each mobile operating system needs independent development projects to provide different experiences for different platforms.
* Slow release of new releases.
* Downloads are user controlled and many users are reluctant to download updates
* App store release review cycle is long.
* Android takes between one and three days, while iOS takes longer
### Web app
#### Advantages
* No need to install the package, saving mobile phone space
* Overall light weight, low development cost
* The user is not required to update manually, but the app developer will update directly in the background, and the new version will be pushed to the user, which is more convenient for business development
* Browser-based, cross-platform
#### Disadvantages
* The page jumps arduous, unsteady sense is stronger.
* When the speed of the network is limited, there are many times when the card or card dead phenomenon, interaction effect is limited
Security is relatively low and data can be easily compromised or hijacked
### Hybrid app
#### Such apps combine the advantages of the above two apps
* On the premise of realizing more functions, the app installation package should not be too large
* Open a web page within the application without the hassle of jumping to the browser
* When the main functional areas are relatively stable, the added functional areas adopt web form, which makes the iteration more convenient
* Web pages are rendered differently when users set different web formats
## Hybrid App implementation principle
### (一)Native calls JS
![Native calls JS](https://images2015.cnblogs.com/blog/745803/201602/745803-20160225172611943-468311561.png)
### （二）JS calls Native
![JS calls Native](https://images2015.cnblogs.com/blog/745803/201602/745803-20160225172707693-462455039.png)
## Technical features of Web App, Hybrid App and Native App
![](http://image.woshipm.com/wp-files/2014/12/b0cf05c189c1814380709ec94ebd5a7b.png)
## Development suggestion
### In the specific development process, what kind of app should be adopted
* If large paragraphs of text (such as news, strategy, etc.) appear in the app, and the format is relatively rich (such as bold, various fonts, etc.), it is better to use H5.<br>
　Reason: native development is not very friendly to parsing the json string format
* If you pay attention to the response speed of app (including the smoothness of page switching), use native development.<br>
　Reason: H5 is essentially a web page. When you change pages, you basically load the entire page, just like a browser opens a new web page
* If the app is sensitive to the presence or absence of the network (such as offline operation or online operation), it shall be developed natively.<br>
　Although H5 can be done, it is sensitive
* If the app wants to make frequent calls to hardware devices (such as cameras, microphones, etc.), it adopts the native development, which supports more hardware and makes the call faster than H5
* If the common pages of app users are frequently-changed (such as various marketing activities on the home page of taobao), it is easier to use H5 for maintenance
* If the budget is limited (H5 develops a suite that can be used across android, iOS, blackberry, etc.) and doesn't care about user experience or load speed, it's H5
## Reference
* [web app 、native app、hybrid app比较](https://www.jianshu.com/p/24bf070a4dcb)
* [Native App vs Web App 以及 Hybrid App的实现原理](https://www.cnblogs.com/alice626/p/5217759.html)
* [web app、native app、hybrid app之间的差异](https://blog.csdn.net/qq_33748378/article/details/51320890)
