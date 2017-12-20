1.

body = document.body
profilePicture = body.querySelector('img.profile-image');
profilePicture.src ="https://placebear.com/400/400"

1.

var skyPhoto = body.querySelector('#left-image > img')
skyPhoto.src = "https://placebear.com/325/225"

2.

var title = body.querySelector('body > section > div:nth-child(1) > h1')
title.innerText = "Sharon the Bear"

3.

var employmentHeader = body.querySelector('#employment > h3')
employmentHeader.innerText = "Doin' Stuff"

4.

body.style.backgroundColor='teal'

5.

var highlights = body.querySelectorAll('.highlight');
var colours = ["blue", "black", "red", "green", "purple", "pink", "lavender", "cyan"];

for (index = 0; index < highlights.length; index ++){
  var randomColour = colours[Math.floor(Math.random()*colours.length)];
  highlights[index].style.backgroundColor = randomColour;
}


6.
title.style.fontFamily = 'monospace'

7.

var roundIcons = body.querySelectorAll('a.action-icon-bg')

roundIcons.forEach(function(roundIcon)
{roundIcon.style.backgroundColor = "black"}
)

8.

var ContactName = body.querySelector('#name')
ContactName.placeholder="Identify Yourself"

9.

var ContactMessage = body.querySelector('#message')
ContactMessage.placeholder = 'State Your Business'

10.

ContactName.value = "Your Nemesis"

11.

var ContactEmail = body.querySelector('#email')
ContactEmail.value ='koalathebear@gmail.com'

12.

var SubmitButton = body.querySelector('#submit')
SubmitButton.value = 'En Garde!'

13.

SubmitButton.disabled= true

14.

var PersonalInfo = body.querySelector('.bio-info')
PersonalInfo.hidden = true
