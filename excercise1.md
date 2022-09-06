<h1>Excercise 11.1</h1>
Application is coded with java. 6 people team is working on it and it will be released soon. 

<h2>Linting</h2>
 Linting depends somewhat on what file types we need to work with. Checkstyle seems to be a popular option that is regularly maintained. it can also be used through plugins in popular code editors.

<h2>Testing</h2>
JUnit is a popular choice for java testing. I's specially made for unit testing. If we need to be testing in several browsers, theres selenium for that. Selenium is open-source browser automation tool that can be used for functional testing. 

<h2>Building</h2>
Maven is currently the number one build tool for java. Second choice would be gradle which uses it's own language for configuration. Maven uses XML for configuration which makes it faster to learn.

<h2>CI setup alternatives besides jenkins and github actions</h2>
Googles number one suggestion for CI/CD cloud is Google cloud(duh!). Distant second suggestion is amazons cloud(which is more popular than sliced bread).

<h2>Self hosted vs. cloud</h2>
Self hosted allows more control and freedom in configuration but also more work. Cloud is usuallu simpler if we can find a service that fits our specs. 
If we need to access to actual hardware then cloud service is a no go.
Cloud service might not be scalable as we need separate server. In a self-hosted setup it is usually possible to upgrade to a bigger server