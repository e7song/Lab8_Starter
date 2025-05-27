# Lab8-Starter

### Name

Eric Song

### GitHub Pages URL

https://e7song.github.io/Lab8_Starter/

### Graceful Degradation and Service Workers

Service workers represent a way to do graceful degradation. A previous definition of graceful degradation mentions that we do our development with maximum performance in mind (i.e., we assume that the users have the latest browser, reasonably good hardware, reasonably fast internet access, etc.). Then, when we encounter cases where this is not necessarily true, graceful degradation dictates that we try and deal with these cases with "grace" (i.e. achieving some sort of minimal performance that still gets the point across). By using this idea, we can hopefully achieve an application where the users experience solid performance when they can and functional performance when it is necessary. When we use service workers in this lab, we are using them to intercept network requests and manage our cache for us. This is an example of graceful degradation. First, we assume that the user has internet access. After making this assumption, we load in our website from various network requests. Later on, if the user loses this internet access, our site can still deliver whatever it was able to save from previous requests. In this way, are addressing a "lower level" with grace.

### pwa.png

[pwa.png](PWA.png)
