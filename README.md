<p align="center">
    <img src="https://drive.google.com/uc?id=1YRVlOBDGISqbSzAgHk0WqihcIbsaF5G7" width="30%">
</p>

<h2>Introduction:</h2>
<p>Website for openhack hackathon. (yet prototype) </p>
<p>P.S: If the logo isn't displaying correctly -- who uses light theme yaar? go change your theme first.</p>

<h2>Installation</h2>
    <p>run <code>npm install</code> from root.</p>
    <p>latest version of React can cause some issues with <code>react-scroll</code> (at least, it did for me). if you face any issues, <a href="https://docs.npmjs.com/cli/v7/commands/npm-cache">clean npm cache.</a> and make sure that installed react version is <code>16.10</code>. if it still doesn't solve your problem, you know <a href="https://stackoverflow.com/">Stack Overflow</a> is the way to go; or feel free create an issue here.</p>

<h2>Build and Deployment</h2>
    <p> <code>npm run build</code> <code>Serve -s build</code> </p>
    <p> you'll need serve to be globally installed. </p>

<h2>Overview and Project Structure:</h2>    
    <p>Ignoring all the typical boilerplate stuff, the <code>src</code> is the main folder. which includes <code>components</code>, <code>images</code> and <code>pages</code> directory. pages contain index.js, which exports the one and only home page of the site.images contain SVGs used in page, being the logo and the one used in about section of the page.</p>
    <p>components contains a folder per every section of the website, being <code>HeroSection</code>, <code>About</code>, <code>Schedule</code>, <code>Problem Statements</code> etc. numbered so we don't have to find them every time trying to change them. (alphabetical sort can be pain in the * sometimes) and separate folders for navigation bar, side bar, logo, card and cardlist components. CardList and Card components are used to display the cards of team and judges section. These all components are imported in pages/index.js file.</p>
    <p><code>ButtonElements.js</code> and <code>Commons.js</code> files include css for button and common css elements such as Container and Wrapper. The actual component inside every folder lies within index.js file. there could be an extra file with <code>componentElements.js</code>, it doesn't bite. It contains css specifically used for that component only. Schedule component contains the Timeline.js file, which exports the timeline used in schedule section of the webpage. don't you ever get tired of reading? shoo have some life.</p>
    
<h2>Todo:</h2>
<ul>
    <li>add social media icons for profile card</li>
    <li>add appropriate data inplace of lorem ipsum.</li>
    <li>add working social media links</li>
    <li>add problem statements, prizes, sponsors, judges and FAQ.</li>
    <li>populate teams with some real data.</li>
    <li>Update favicon icon and document title</li>
    <li>drink some water</li>
</ul>

<h3> Live: https://iei-openhack.herokuapp.com/</h3>

<h4>Suggestions? Want to contribute? Pull requests are always open.</h4>
<ul>
<li>Fork it</li>
<li>Clone it to your local system</li>
<li>Make a new branch</li>
<li>Make your changes</li>
<li>Push it back to your repo</li>
<li>Click the Compare & pull request button</li>
<li>Click Create pull request to open a new pull request</li>
</ul>

Have a nice day :)
