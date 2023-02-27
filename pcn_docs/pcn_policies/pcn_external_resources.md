# Controlling External Sources Policy

Controlling external sources is an important aspect of web security as loading resources from external sources can introduce security risks to web applications. External sources refer to resources that are hosted on a different domain than the web application being accessed. This includes scripts, images, stylesheets, fonts, and other types of content.

One of the main risks associated with loading resources from external sources is the possibility of introducing malicious code into the web application. Malicious actors can host malicious code on external domains, and if the web application loads that code, it can execute on the user's device and potentially compromise their security and privacy.

Another risk associated with loading resources from external sources is that the external sources may not be available or may be compromised, leading to a degraded user experience or other security issues.

Here are our coding practices that a developer must follow to implement a local file only policy:

- **Load resources from the same domain:** All resources, including scripts, images, and stylesheets, should be hosted on the same domain as the web application. Avoid loading resources from external domains.
- **Use relative URLs:** When referencing resources, use relative URLs instead of absolute URLs. This ensures that the resources are loaded from the same domain as the web application, even if the web application is deployed on a different server.
- **Use HTTPS:** When loading resources, use HTTPS to ensure that the resources are loaded securely. This prevents third parties from intercepting or modifying the resources.
- **Sanitise user input:** When accepting user input, sanitise it to prevent malicious code injection. This includes input from forms, URLs, cookies, and stored database resources.

By following these coding practices, a developer can implement our local file only policy that restricts the loading of external resources and ensures that resources are loaded securely.