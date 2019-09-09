## Topic & Motivation

### Theme / Topic

Title: **Building a static site with Gatsby.js + How to use GraphQL with Kentico Cloud**

* What is Static site generator and its benefits, what is Gatsby and how to use it with Kentico Cloud to reach that benefits.
* It is possible to use GraphQL with Kentico Cloud

### Target role

* Developers, CTOs

### Transformation

* Consider using static site for client projects
* Understand static sites benefits
* Static site does not mean a set of HTML files

## Outline

* What is static site?
  * What does the static mean (no plain HTML from 90's)
  * What is static site
  * Performance benefit
  * Security benefit
 
* What is a static site generator?
  * What is Gatsby (React)
  * What is GraphQL
  * GraphQL vs REST API
  * Where does it take content?
  * Easy content management in headless CMS
  * Automatic rebuild via webhooks
 
* Starting with Gatsby
  * Show how KC Gatsby source plugin works
  * Kentico Cloud content structure in Gatsby GraphQL content model
  * Start from content structure -> Reusable components
  * Showcase on one complex model -> Company intranet with personal space
  * Show Graph iQL interface
    * Possibly use Material descign framework for react (https://demos.creative-tim.com/material-dashboard-react/#/admin/dashboard)
    * https://app.kenticocloud.com/09fc0115-dd4d-00c7-5bd9-5f73836aee81/content-models/types
    * User name + surname -> connect in Gatsby 
    * rich text used to create a personal BIO, landing page
    * Multilingual links
    * Type -> Itemsl links
    * Element types resolition
      * Standard types (text, datetime, radio, taxonomy)
      * Linked element resolution
      * Rich text item reolution
        * embedded resolution in JS SDK
        * resolve rich text to a structured React components
 
* Deploying static site
  * Generating static site
  * Publishing static site
  * Updating content on static site
  * CI/CD of static site
  * Deploy showcase and add the link + QR code to the presentation
  
* Who is running static?
* How else use GraphQL with Kentico Cloud?
 
* Interested in static site generator - meet us and the stand
