<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title>Rakesh Vadnala</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Hai, I'm Rakesh Vadnala, i'm a Pentester, Programmer, Techie Geek, Photographer and Software enthusiast " />
  <meta name="keywords" content="rakesh, techie rakesh, rakesh techie, rakeshvadnala, vadnalarakesh, rakesh vadnala, vadnala rakesh, techgeek, tech geek, techgeeks, tech person, tech guy, techie boss" />
  <meta name="author" content="Rakesh Vadnala" />
  <link rel="shortcut icon" href="favicon.ico">
  <link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.4/css/bulma.min.css'>
  <link rel="stylesheet" href="./style.css">

</head>
<body>
<!-- partial:index.partial.html -->
<section class="hero is-fullheight">
  <div class="hero-body">
    <div class="container">
      <div class="columns">
        <div class="column is-3 is-flex">
          <div class="column-child sidebar shadow">
            <div class="sidebar-header has-text-centered">
              <img
                src="https://media-exp1.licdn.com/dms/image/C5603AQHn6D7x6lXxVA/profile-displayphoto-shrink_400_400/0?e=1605139200&v=beta&t=70DY3hsRfrsYDy5_-rIQV5KrPG0bgdbAJYzpxV9_AS8" alt="Avatar"
                class="sidebar-image">
              <h2 class="header-name">Rakesh Vadnala</h2>
              <h5>Software Enthusiast, Programmer, Pentester, Photographer</h5>
              <div class="social-icons">
			    <a href="https://www.linkedin.com/in/rakeshvadnala"><i class="fab fa-linkedin icon"></i></a>
				<a href="https://github.com/rakeshvadnala"><i class="fab fa-github icon"></i></a>
                <a href="https://twitter.com/Rakeshvadnala"><i class="fab fa-twitter icon"></i></a>         
                <a href="https://www.instagram.com/rakeshvadnala/"><i class="fab fa-instagram icon"></i></a>
				<a href="https://www.sololearn.com/profile/1170667/"><i class="fab fa-sololearn icon"></i></a>
				
              </div>
              <!-- <div class="resume">
                <a href="./resume.pdf" class="sidebar-link">
                  Resume
                </a>
              </div> -->
            </div>
          </div>
        </div>
        <div class="column is-flex">

          <div class="column-child terminal shadow">
            <div class="terminal-bar dark-mode">
              <div class="icon-btn close"></div>
              <div class="icon-btn min"></div>
              <div class="icon-btn max"></div>
              <div class="terminal-bar-text is-hidden-mobile dark-mode-text">root@h4ckup ~</div>
            </div>

            <div class="terminal-window primary-bg" onclick="document.getElementById('dummyKeyboard').focus();">
              <div class="terminal-output" id="terminalOutput">
                <div class="terminal-line">
                  <span class="help-msg">H3ll0! W3lc0me t0 b4sh : Type <span class="code">help</span>
                    for commands.
                    </span>
                  </span>
                </div>
              </div>
              <div class="terminal-line">
                <span class="successl">root@h4sh</span> <span class="directory">#</span> <span class="user-input"
                  id="userInput"></span>
                <input type="text" id="dummyKeyboard" class="dummy-keyboard">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="footer">
    <div class="content has-text-centered">
      <p>
        Designed by @Rakeshvadnala
	</p>
    </div>
  </footer>
</section>
<style>

<style> 

body {
    margin: 0;
    height: 100%;
}

body, footer, .hero-body {
    background-color: rgb(10, 25, 47) !important;
}

a {
    color: inherit;
}

a:hover {
    text-decoration: none;
    color: inherit;
}

p {
    color: rgb(136, 146, 176);
}

.title {
    color: rgba(139, 180, 216, 0.94);
}

.sidebar {
    background-color: rgb(23, 42, 69);
    display: flex;
    align-items: center;
    flex-direction: column;
    border-radius: 5px;
    color: rgb(136, 146, 176);
    opacity: 1;
}


.image-overlay {
    background: url('https://i.imgur.com/SsVBVWk.png') 20%;
    opacity: 0.5;
}

.sidebar-image {
    width: 150px;
    border-radius: 100%;
    margin-top: 1rem;
    text-shadow: 2px 2px 4px #000000;
}

.sidebar-link {
    font-size: 0.8rem;
    text-transform: uppercase;
    color: rgba(139, 180, 216, 0.94);
}

.sidebar-link:hover {
    color: rgb(230, 241, 255);

}

.header-name {
    font-weight: 600;
    color: rgb(230, 241, 255);
}

.column-header {
    border-bottom: 2px rgb(45, 57, 82) solid;
    margin-bottom: 1rem;
}

.column-header > h1 {
    font-family: 'Lato', sans-serif;
    font-weight: 100;
    color: white;
}

.icon, .sidebar-link {
    transition-duration: 250ms;
}

.icon:hover {
    color: white;
}

.terminal-bar {
    background-color: #eae8e9;
    border-top-left-radius: 5px;
    border-top-right-radius: 5px;
    display: flex;
    position: relative;
}

.dark-mode {
    background-image: linear-gradient(180deg, #464248 0%, #3b383d 100%);
    border-bottom: 1px solid rgba(66, 66, 66, 0.5);
}

.dark-mode-text {
    color: #bdb9bf !important;
}

.icon-btn {
    border-radius: 50%;
    margin-top: 7px;
    height: 15px;
    width: 15px;
    margin-bottom: 0.5rem;
}

.terminal-bar > div.icon-btn:first-child {
    margin-left: 0.6rem;
}

.terminal-bar > div.icon-btn:not(:first-child) {
    margin-left: 0.5rem;
}

.terminal-bar > div.icon-btn:last-child {
    margin-right: 0.6rem;
}

.close {
    background-color: #fa615c;
}

.max {
    background-color: #3fc950;
}

.min {
    background-color: #ffbd48;
}

.terminal-window {
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    height: 254px;
    padding: .5rem 0rem 0rem .5rem;
    display: flex;
    flex-direction: column;
}

.primary-bg {
    background-color: rgb(23, 42, 69);
}

.shadow {
    -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.55);
    -moz-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.55);
    box-shadow: 0px 3px 15px rgba(0, 0, 0, 0.2);
}

.terminal-bar-text {
    position: absolute;
    margin-top: 3px;
    color: #383838;
    width: 100%;
    text-align: center;
    font-weight: 500;
}

.has-equal-height {
    height: 100%;
    display: flex;
    flex-direction: column;
}

.terminal-output {
    overflow-y: hidden;
    overflow: auto;
}

.column-child {
    flex: 1;
}

.terminal-line {
    position: relative;
    font-family: 'Anonymous Pro', monospace;
    font-size: .9rem;
    color: #b7c5d2;
}

.directory {
    color: #75e1e7;
    font-weight: 500;
}

.success {
    color: #8dd39e;
}

.successl {
    color: #d92027;
}

.code, .error, .fa-heart {
    color: #d7566a
}

.fa-heart {
    padding-top: 0.5rem;
}

.dummy-keyboard {
    /*background-color: #172a45;*/
    background-color: transparent;
    color: #b7c5d2;
    font-family: 'Anonymous Pro', monospace;
    font-size: 0.9rem;
    caret-color: #b7c5d2;
    padding-left: 0;
    outline: none;
    border: none;
}
.dummy-keyboard:focus{
    outline: none;
    text-decoration: none;

}

::-webkit-scrollbar {
    display: none;
}

@media screen and (max-width: 768px) {
    .resume {
        padding-bottom: 0.5rem;
    }
}


</style>

</style>

<script>
const COMMANDS = {
  id:
    'uid=0(root) gid=0(root) groups=0(root)',
  proj:
    "<a href='https://github.com/rakeshvadnala/wasender' class='success link'>Whatsapp Automation</a>, <br> \
	<a href='https://github.com/rakeshvadnala/LearningWithPy' class='success link'>Python Projects</a>, <br> \
    <a href='https://arduinoprojectsall.blogspot.com/' class='success link'>Arduino and IoT Projects</a><br>",
  help:
    'Commands: <span class="code">about</span>, <span class="code">exper</span>, <span class="code">edu</span>, <span class="code">skills</span>, <span class="code">proj</span>, <span class="code">contact</span>',
  about:
    "Hey! 👋<br>I'm Rakesh. I'm a Techie Geek and Software Enthusiast, I live for challenging adventures with the intent of making myself productive and also gaining inexperienced experience in this modern advanced cybersecurity world.",
  skills:
    '<span class="code">Languages:</span> Python, Java, C, SQL<br><span class="code">Technical:</span> Network Pentesting, Kali Linux, System Administration, Vulnerability Assessment, Bash Scripting<br><span class="code">Tools:</span> Metasploit Framework, Nmap, Burpsuite,Maltego, MSFVenom, Wireshark.',
  edu:
    "Vaagdevi Engineering College -Electrical and Electronics Engineering, 2015-2029<br> Ramappa Junior College - 2013-2015",
  // resume:
  //   "<a href='./resume.pdf' class='success link'>resume.pdf</a>",
  exper:
    "I was worked in Jugnoo as an Operational Executive. <br>In College days, I worked as Arudino Mentor<br>",
  contact:
    "You can contact me on any of following links:<br><a href='https://www.linkedin.com/in/rakeshvadnala/' class='success link'>LinkedIn</a> ,<a href='https://www.instagram.com/rakeshvadnala//' class='success link'>Instagram</a>, <a href='https://twitter.com/Rakeshvadnala' class='success link'>Twitter</a>"
};
let userInput, terminalOutput;

let prevInputs = [];
let lenUp = -1;

const app = () => {
    userInput = document.getElementById("userInput");
    terminalOutput = document.getElementById("terminalOutput");
    document.getElementById("dummyKeyboard").focus();
    console.log("Application loaded");
};

const execute = function executeCommand(input) {
    let output;
    input = input.toLowerCase();
    if (input.length === 0) {
        return;
    }
    output = `<div class="terminal-line"><span class="success">➜</span> <span class="directory">~</span> ${input}</div>`;
    if (!COMMANDS.hasOwnProperty(input)) {
        output += `<div class="terminal-line">no such command: ${input}</div>`;
        console.log("Oops! no such command");
    } else {
        output += COMMANDS[input];
    }

    terminalOutput.innerHTML = `${
        terminalOutput.innerHTML
        }<div class="terminal-line">${output}</div>`;
    terminalOutput.scrollTop = terminalOutput.scrollHeight;
    userInput.innerHTML = input;
    prevInputs.push(input);
    lenUp = prevInputs.length - 1;
    document.getElementById('dummyKeyboard').value = ''
};

const key = function keyEvent(e) {

    const input = document.getElementById('dummyKeyboard').value;
    if (e.key === "Enter") {
        execute(input);
        userInput.innerHTML = "";
    }


};

const backspace = function backSpaceKeyEvent(e) {

    if (e.key !== 'Backspace' && e.key !== 'Delete' && e.key !== 'ArrowUp' && e.key !== 'ArrowDown') {
        return;
    }

    if (e.key === 'ArrowUp' && lenUp !== -1) {
        document.getElementById('dummyKeyboard').value = prevInputs[lenUp];
        lenUp--;
        if (lenUp < 0)
            lenUp = prevInputs.length - 1;

        return;
    } else if (e.key === 'ArrowDown' && lenUp !== -1) {

        lenUp++;
        if(lenUp===prevInputs.length)
            lenUp=0;

        document.getElementById('dummyKeyboard').value = prevInputs[lenUp];

        return;

    }
    userInput.innerHTML = userInput.innerHTML.slice(
        0,
        userInput.innerHTML.length - 1
    );
};


document.addEventListener("keydown", backspace);
document.addEventListener("keypress", key);
document.addEventListener("DOMContentLoaded", app);

</script>


<!-- partial -->
  <script src='https://use.fontawesome.com/releases/v5.3.1/js/all.js'></script><script  src="./script.js"></script>

</body>
</html>
