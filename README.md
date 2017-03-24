# Atomic Emails
This is a blue-print design system based off of Atomic Design using the MJML framework to create a sustainable, reliable and consistent system for developing responsive emails. 

* [Atomic Design](http://bradfrost.com/blog/post/atomic-web-design)
* [MJML Framework](https://mjml.io)

I also highly recommend Brad Frost's [Atomic Design Book](http://atomicdesign.bradfrost.com).

## Install MJML
Follow the instructions to install MJML, you can find it in thee [MJML documentation](https://mjml.io/documentation) or on their [MJML Git Repo](https://github.com/mjmlio/mjml). MJML requires [Node.js](https://nodejs.org/en/) and I highly recommend using their syntax libraries for [Sublime](https://github.com/mjmlio/mjml-syntax) or [Atom](https://atom.io/packages/language-mjml).

# Atomic Design for Emails
While Atomic Design was originally intended for a website or a webapp, it's also true that the same concept can be applied for a mobile app, so what not for emails? :scream_cat: :boom: For a design system or [Pattern Lab](http://demo.patternlab.io/), we don't need nearly all the components a website or mobile app need. Here is a list of all the atoms, molecules, organisms, and templates and finally instead of pages, I'm going to call them what they are, emails.

I should also note that when I came up with this list it was in the mindset of designing for an ecommerce platform, the system would require to be able to do both marketing and transactional emails. If there's something I left out, or something you think I did worng, feel free to make a pull request. :kissing_smiling_eyes:


## Atoms 

#### Colors
* Brand Colors
* Neutral Colors
* Utility Colors

#### Typography
* Fonts
* Headlines
* Horizontal Rule

#### Inline Elements
* Text Link
* Strong
* Emphasis
* Underline
* Strikethrough
* Small
* Buttons
* Inline Images
* Icons

#### Block Elements
* Paragraph
* Block Images
* Unordered Lists
* Ordered Lists
* Sections
* Table Headers
* Table Body
* Table Rows
* Table Cells
* Panels Headers
* Panels Rows


## Molecules 
* Primary Navigation
* Secondary Navigation
* Footer Navigation
* Heros
* Cards

## Organisms 
* Container
* Section
* Header
* Footer
* Tables
* Panels

## Templates
* Basic Layout 

This will be the entire email with all the pieces put together but without any content. It will consist a header, followed by a blank section for content and ending with a footer. More templates maybe to come.

### Transactional
* Plain Text
* Welcome 
* Reset Password 
* Notify Member of Account Change 
* Order Confirmation
* Invite
* Invite Recieved
* Invite Fulfilled

### Marketing
* Normal Promotion
* Sale Promotion
* Content Promotion
* Recommended Promotion
* Invite Friends Promotion
* Abandonded Cart

## Emails
:boom: :dizzy: :rocket: 

Depending how your ESP and how you're actually adding content to your emails, chances are it's dynamically fed in though an API or some other means. Point being, the "email" is what the user is actually recieving, for many, it maybe not be something you see until it's actually sent. For others, you may want to consider moving all the transactional and marketing templates from "templates" to "layouts", depending on if you have hardcoded content or dynamic content. 

































