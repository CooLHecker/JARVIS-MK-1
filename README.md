# JARVIS-MK-1
Voice assistant based on the fictional AI assistant used by tony stark in the movie iron man.
Commands you can use-

open instagram

open calculator

open discord

<h5>Note</h5> adjust the links in js file as per your needs-

if (message.includes("hey") || message.includes("hello")) {

    const finalText = "Hello Boss";
    
    speech.text = finalText;
    
 
 } else if (message.includes("how are you")) {
    
    const finalText = "I am fine tell me how can i help you";
    
    speech.text = finalText;
  
  } else if (message.includes("your name")) {
    
    const finalText = "My name is JARVIS";
    
    speech.text = finalText;
  
  } else if (message.includes("open discord")) {
    
    window.open("https://discord.com/channels/@me");
    
    speech.text = finalText;
  
  } else if (message.includes("your site")) {
    
    window.open(
    
    "Your link
    
    );
    
    }
    
    
<h2>PREVIEW</h2>

![JARVIS - Virtual Assistant - Google Chrome 08-10-2022 15_27_43 (2)](https://user-images.githubusercontent.com/114807496/194701828-81e36c87-b3b3-44cb-878a-371a1e534992.png)
