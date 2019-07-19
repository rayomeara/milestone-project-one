
Website to promote a famous 1960's band who are keen in giving their fans a 
resourse site for all their old and future hits. 

The band also want a site that allows for bookings to to special events and a 
means of showing their availability for the year.

---
### UX

I had a lot of difficulty coming up with ideas as to how the site should look. 
In the end, I went with a look that was simple, vibrant with colour and with all
the functionality that would be needed for the bands needs. I also wanted to 
make the site a throwback to the 60's, so that it looked like something of the 
period so that old fans are familiar and that new fans can appreciate their 
origins. The site is also very reactive to the different devices that it would 
be used from, so anyone who uses it from a phone, tablet or desktop should have 
a good experience and find it easy to get what they want from the site.
Wireframes from the project can be found in the 'wireframes' folder.

https://github.com/rayomeara/milestone-project-one/tree/master/wireframes

The site handles many different users:
* A new user coming to the site can read the home page and click on links to go to
the music offerings. 
* Old fans can go to the music directly and download their favourites. 
* For the users curious as to the bands origins, they can read all the info and 
band details in the _About_ section. 
* Fans wanting to get in touch can leave messages using the _Contact_ application 
form, email or postal address.
* People visiting to book the band can read the list of bookings and apply for a
booking themselves

---
### Technologies

HTML5,
CSS3,
Bootstrap 4.3.1,
FontAwesome 4.7.0

---
### Features

The site employs the basic funstionality for a band. Welcome and about pages to 
introduce the members to new fans, a songs page that has some of the bands songs 
for people to listen to and download for themselves. A bookings page which will 
give a list of all dates that the band are currently booked for and an 
application form to allow anyone to book the band on dates of their choosing 
(availability allowing of course). There is also a page to allow for fans to 
contact the band either through the page, through email or by post.

---
### Features to do

The site still needs to have the social links and email links done so as to 
point to actual media. There was also a problem with employing the video 
provided by the band on the site. It apprears that the video compression is not 
recognized by the video HTML5 component so new material is needed. The date
labelling is also a hack for Chrome, so for other browsers, a better
implementation would be needed.

---
### Testing

The testing for this app was focused on 2 different types of user. Firstly, one
who already knows the band and secondly, people who have never heard of the band
and have come to learn more. So I had use cases who were coming to the site with
specific cases in mind e.g. wanting to listen to tracks or book for an event.
With that in mind, the menu links at the top of the page work excellently. For 
newer users, they may want to take an initial read of the intro page to learn
what the site is. For this purpose, links are included in this page so that a
user can go to the music section or to the bookings if they like what they have
read.
The forms have all details as manditory, as this is the basic details needed for
a booking request or contact request. The email field is also being validated
to ensure that the email submitted is a valid one.
The email link provided on the contact page will open the default email client
used on that machine and open an email to send to the band's email.
This site was tested across multiple browsers (Chrome, Internet Explorer, 
FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome, iPad, 
Samsung Galaxy) to ensure compatibility and responsiveness.

---
### Deployment

The site is currently being hosted at:

https://rayomeara.github.io/milestone-project-one/

And is deployed directly from the master branch. The site update automatically
upon new commits to the master branch.

To run locally, clone the repository using the command:

git clone https://github.com/rayomeara/milestone-project-one.git
