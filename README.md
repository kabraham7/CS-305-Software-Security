# CS 305: Software Security Portfolio

## Project Overview

This repository contains my Artemis Financial Practices for Secure Software Report from CS 305. The project focused on improving the security of an existing software application and checking that it continued to function after the changes.

## Client and Software Requirements

Artemis Financial is a financial consulting company that develops personalized financial plans for its customers. The company wanted to improve the security of its web application and protect sensitive information. My work involved adding checksum verification, configuring secure communication through HTTPS, and reviewing the application for security vulnerabilities.

## Identifying Vulnerabilities and Coding Securely

One thing I did well was using the project requirements to guide my security changes and reviewing the application’s dependencies with OWASP Dependency-Check. This helped me understand that security problems can come from both the code developers write and the third-party libraries an application uses. Coding securely is important because weaknesses can expose sensitive information or allow unauthorized access. Software security helps a company protect its customers, maintain trust, and reduce disruptions to its business.

## Challenges and Helpful Parts of the Assessment

One challenging part was getting the dependency-check scan to run correctly and understanding the report. I experienced problems with the vulnerability data updates, which showed me that security tools also require proper configuration and troubleshooting. Reviewing the report was helpful because it gave me practice identifying affected dependencies and considering what needed further investigation.

## Adding Layers of Security

I increased the application’s layers of security by configuring HTTPS, generating a self-signed certificate for local testing, and adding a SHA-256 checksum to help verify data integrity. These measures serve different purposes: HTTPS protects information during transmission, while the checksum helps detect changes to data. In future projects, I would use dependency scanning, static analysis, manual code review, and functional testing to assess vulnerabilities. I would choose mitigation techniques based on the severity of each issue, how it could be exploited, and its effect on the application.

## Checking Functionality and Security

After refactoring the application, I ran it and checked the HTTPS endpoint and checksum output. I also used OWASP Dependency-Check to review the dependencies for known vulnerabilities. Reviewing the results alongside my code changes helped me look for remaining issues. These checks increased my confidence in the application, although they did not prove that it was free of every possible vulnerability.

## Useful Resources, Tools, and Practices

The tools and resources I used included Java, Spring Boot, Eclipse, Maven, Java keytool, and OWASP Dependency-Check. The course materials and project instructions helped me understand how to apply these tools. Practices such as making small changes, reviewing error messages, checking dependencies, and testing after refactoring will be useful in future assignments and software development work.

## What I Would Show Future Employers

I would show future employers my completed Artemis Financial Practices for Secure Software Report as an example of my ability to apply basic software security practices. The report demonstrates my experience with secure communication, checksum verification, certificate generation, and dependency analysis. It also shows how I documented my work and explained the reasons for my security decisions.
