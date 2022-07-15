# gellany_autoinput

<code>sudo apt install expect</code><br>

<code>./questions.sh</code><br>
<code>Hello, please introduce yourself.</code><br>
<code>Your name: ahmed</code><br>
<code>Are you human?</code><br>
<code>y/n: y</code><br>
<code>What is your favorite programming language?</code><br>
<code>Your answer: python</code><br>

<code>Answers:</code><br>
<code>1. ahmed</code><br>
<code>2. y</code><br>
<code>3. python</code><br>

<code>printf "bot\nn\nJava" | ./questions.sh</code><br>
<code>Hello, please introduce yourself.</code><br>
<code>Your name: Are you human?</code><br>
<code>y/n: What is your favorite programming language?</code><br>
<code>Your answer: </code><br>
<code>Answers:</code><br>
<code>1. bot</code><br>
<code>2. n</code><br>
<code>3. Java</code><br></code><br>

<code>./gellany_autoinput.sh</code><br>
<code>.spawn ./questions.sh</code><br>
<code>.Hello, please introduce yourself.</code><br>
<code>.Your name: expect</code><br>
<code>.Are you human?</code><br>
<code>.y/n: n</code><br>
<code>.What is your favorite programming language?</code><br>
<code>.Your answer: Java</code><br>

<code>.Answers:</code><br>
<code>.1. expect</code><br>
<code>.2. n</code><br>
<code>.3. Java</code><br>
