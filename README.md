<h1>SESSION 01, WEEK 01</h1>

<h2>Questions 1 & 2</h2>
<ol>
  <li>Interpreted And Compiled Programming Languages</li>
  <p>
    <ul>
      <li>Complied</li>
      <p>This type of program compiles, assembles or puts together the source code into an executable file. This file can be read by another machine with the same machine code. Observations: Faster, ready to run, source code is private, takes an extra step (compile), not cross-platform (pc and mac).</p>
      <li>Interpreted</li>
        <p>This tyoe of program makes a copy of the source code (public). Observations: Cross platform, simpler to test, needs an interpreter (slower).</p>
  </ul>
  <li>Is Java compiled or interpreted, or both?</li>
  <p> Java is first a compiled into bytecode (by the Java compiler/JRE), bytecode is then interpreted by a Java Virtual Machine (JVM). Modern JVMs use JIT (Just in Time compilation) to compile the bytecode to native machine language.</p>
</ol> 

<h2>Pseudocode currency converter</h2>
  <ol>
  <li>START</li>
  <li>rate = Get 1USD TO BTC current exchange rate from google</li>
  <li>amount = 0</li>
  <li>amount = ask user for the amount in USD</li>
  <li>final_amount =rate * amount</li>
  <li>print final amount</li>
  <li>END</li>
  </ol>


<h1>SESSION 03, WEEK 01</h1>

for (let i = 0; i<101; i++) { 
    if (i % 2 ==0){
        console.log(i);
    }
}

Bad code
var cond = false;

if ((cond == true)) {
  console.log('The cond variable is true');
} else {
  console.log('The cond variable is false');
}


Bad code 2

var n = 100;
if (n == 100){
    console.log("This is a special number!");
} else{
if (n<1000){
    if (n % 10 == 0){
        console.log("this number is almost special");
    }
}

else {
    console.log("This number just a regular number")
}
}


Holiday VIII - Duty Free
function dutyFree(normPrice, discount, hol){
  var bottleTotal= Math.floor((hol/((discount / 100) * normPrice)));

  return(bottleTotal);
}
