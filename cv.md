# Alyona Tammur

## Contacts
* **email:** tammuruonok@gmail.com
* **telegram:** @alyonafuria
* **discord** @alyonafuria

## About me
I've been working as a camerawoman and a video editor for over 6 years and faced different challenges during that time, such as:
 - managing loads of data
 - working under strict deadlines
 - mentoring new staff members
 - communicating with people of all backgrounds
 - solving unconventional technical issues
 - learning new skills fast
 - etc

I strongly believe that my passion, perseverance and above-mentioned experience will help me to become an excellent front-end developer.

## Skills
* HTML
* CSS
* Basic JavaScript
* Git
* Photoshop, Figma
* C *(basics)*

## Code Example

```const APIKey = '30425c3bff3016233a1d64dbafd04b11';
const form = document.forms[0];

let xhr = new XMLHttpRequest();

	form.onsubmit = function (e) {
	e.preventDefault();

	const city = form.elements.city.value;
	const url = 'http://api.openweathermap.org/data/2.5/weather?q='+city+'&appid='+APIKey;

	xhr.open('GET', url, false);

	xhr.send();
	
	if(xhr.status != 200) {
	console.log(xhr.status + ' ' + xhr.statusText);
} else {
	
	let DATA = JSON.parse(xhr.responseText);
	let temperature = document.createElement('h2');
	temperature.textContent = 'Temperature: '+ Math.round(DATA.main.temp - 273) + 'C';
	let windSpeed = document.createElement('h3');
	windSpeed.textContent = 'Wind Speed: '+ (DATA.wind.speed);

	document.body.append(temperature);
	document.body.append(windSpeed);
	}
}
```

## Experience
[Web Dev course at MCS](https://alyonafuria.github.io/WebDev/)

## Education
* Version Control with Git *(Udacity)*
* MosCoding web development course *(HTML, CSS passed, React in progress)*

## English Level
proficient *(majored at university)*
