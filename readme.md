<!DOCTYPE html>
<html>
    <body>
        <h1 align="center"><strong>Canvas Hair Co.</strong><hr>
        <p>Vulnerabilities and Bug Report</h1>
        <p> As a concerned customer, cyber security specialist, and a computer science student, I conducted a security assessment of the Canvas Hair Co. website to identify potential vulnerabilities and recommend measures to enhance the website's security. The purpose of this report is to provide you with valuable insights and actionable recommendations to ensure a safer online presence for your business as it grows in the area. We need to always remember that implementing security might be time consuming, none the less, the easier it is to access something, the less secure it is by default. </p>
        <h2>Vulnerabilities and Recommendations:</h2>
        <ol>
            <li> Misconfiguration of SSL certificate: <ul>
                    <li> Description: Misconfiguration of SSL Certificate and Encryption: The website, http://www.canvashair.co, has an SSL certificate that is not properly configured. </li>
                    <li> Problem: The misconfiguration exposes the company to potential security risks during communication. </li>
                    <li> Attacks: Without proper SSL configuration, attackers may intercept data exchanged between users and the website. <p>
                        <p align="center">
                            <a href="https://youtu.be/UZ1ylx5_V30">
                                <img src="https://img.youtube.com/vi/UZ1ylx5_V30/0.jpg" alt="HTTP Header Manipulation Attacks">
                            </a>
                        </p>
                        </p>
                    </li>
                    <li> Technical Impacts: Data transmitted over the website is not securely encrypted due to the misconfigured SSL certificate. </li>
                    <li> Recommendation: Configure SSL and enable encryption to protect user data and secure communication. </li>
                    <li> Rationale: Implementing SSL will safeguard sensitive user information, build trust with customers, and protect against potential data breaches. </li>
                </ul>
            </li>
            <li> Menu User Interface (UI) Colliding with "canvas-hair-co-logo-2": <ul>
                    <li> Description: Menu jargon and Logo Interference: The presence of "canvas-hair-co-logo-2" code within the text of the webpage is causing UI jargon and disrupting the user interface. </li>
                    <li> Problem: The logo's code is inadvertently mixed with the website's textual content, causing the UI to display incorrectly. </li>
                    <li> Attacks: This vulnerability is not directly exploitable for attacks, but it significantly impacts the readability and aesthetics of the website. </li>
                    <li> Technical Impacts: The website's textual content appears jumbled and visually unappealing due to the presence of the logo code. </li>
                    <li> Recommendation: To resolve the interference issue between the menu UI and the "canvas-hair-co-logo-2," adjust the placement of the "mfn_hook" used for the menu, ensuring it doesn't overlap or interfere with the logo code. </li>
                    <li> Rationale: Properly positioning the menu UI and logo elements will create a cleaner and more visually appealing layout, improving the overall user experience. </li>
                </ul>
            </li>
            <li> Emoji's Display Issue: <ul>
                    <li> Description: Emojis Display Issue: Emojis on the website appear as brackets ([]), indicating a rendering issue. </li>
                    <li> Problem: The incorrect rendering of emojis affects the visual appeal and user experience of the website. </li>
                    <li> Attacks: This vulnerability is not directly exploitable in terms of attacks, but it may lead to reduced customer engagement. </li>
                    <li> Technical Impacts: The website may appear less appealing to users, potentially affecting user retention. </li>
                    <li> Recommendation: Investigate the cause of the rendering issue and implement a fix to ensure proper display of emojis. Whether being emojis or new lines, they deserve attention. </li>
                    <li> Rationale: Enhancing the visual aspect of the website contributes to a positive user experience, which can positively impact customer engagement and loyalty. </li>
                </ul>
            </li>
            <li> Non-functional Links: <ul>
                    <li> Description: Non-functional Links: The "#Contact-Us" and "#The-Salon" links do not lead to the intended destinations. href links in the html are broken due to the mfn_hook creating a bug due to its placement and user interface. </li>
                    <li> Problem: Users are unable to access the desired content or sections due to broken links. </li>
                    <li> Attacks: This vulnerability may not be exploited directly for attacks, but it affects user experience and navigation. </li>
                    <li> Technical Impacts: Users cannot access relevant sections or contact information on the website. </li>
                    <li> Recommendation: Verify the URLs and update the links to ensure they lead to the correct pages or sections. </li>
                    <li> Rationale: Improving navigation and accessibility will enhance user satisfaction and make relevant information readily available. </li>
                </ul>
            </li>
        </ol>
        <h2>Technical Impacts:</h2>
        <ul>
            <li>Non-functional emojis and links may lead to a suboptimal user experience and hinder user engagement.</li>
            <li>Lack of SSL encryption exposes user data to potential interception and unauthorized access.</li>
            <li>UI jargon and logo interference may negatively impact the website’s functionality with the menu and may affect the user’s decision negatively.</li>
        </ul>
        <h2>References:</h2>
        <ul>
            <li>CWE 319 (CWE-319: Cleartext Transmission of Sensitive Information in HTTP): <a href="https://cwe.mitre.org/data/definitions/319.html">https://cwe.mitre.org/data/definitions/319.html</a>
            </li>
        </ul>
        <h2>Contact Information</h2>
        <p> If you have any questions or require additional information, please do not hesitate to contact me. <br>
            <br>
            <code>Email:</code>
            <a href="ryan@rshatch.com">ryan@rshatch.com</a>
            <br>
            <code>GitHub:</code>
            <a href="https://github.com/ryanshatch">ryanshatch</a>
            <br>
            <code>Personal Website:</code>
            <a href="https://ryanshatch.com/resume">ryanshatch.me</a>
        </p>
        <p align="center"> &copy; 2023 Ryan Hatch <br>
            <br>
            <code>I do not own any of this, I am simply contributing towards the safety of my favorite hair salon and contributing towards a new local business.</code>
        </p>
