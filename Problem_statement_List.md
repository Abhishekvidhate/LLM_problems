# <font color = blue>INITAL LIST OF PROBLEM STATEMENTS </font>

## 1. doctor/prescriber for common illeness ( kudos --> mudit gaur ) 
  - a chat-bot like assistant which take prompt from user as input , generates text prescription on the inputed illness 
  - useful for hospitals as commo & basic remedies can be cured easy and simply with no doctor inventions, doctors can focus on  major illness
  - it can be a good benchmark for doctors/med students as the illness our model can't digonasis with/above HLP(here docs,med experts) 
    and provide proper procedure ( actions to take ,like take meds or visit doc based on severity,etc)

 disadvantages with this chat-bot solution :-
 - chat bot can't be a doctor , as eg. for common cold doctors don't directly give you medics, they first check your breathing patterns , tongue , etc 
   then they arrive at conclusion that patients have cold 
 - chat-bot don't have capacity to check for tongue , breathing patterns ( this features are only for common cold , think for a number of diseases we will
   have to add many features to our chatbot also add camera , etc to chat-bot i.e basically too complex )
 - our model must have high recall as false truths can fuck our product 
<!-- Empty line above -->
## 2. train ticket machine( kudos --> dyanesh temgire )
  - machine is too complex and even dyanesh fell it was stupid machine, it needs human supervisioin (mostly TC) provide ticket ,
    basically this machine is too complex for user
  - aksh hinted it can be a OCR machine ( he told it is present at train stations , bus stations , police stations) , this name can be false , as i don't 
    remember him calling it a OCR machine clearly

I CAN ASK PAPPA ABOUT RAILWAY STATION AND ALL TYPE OF PROBLEMS HE THINKS IS A PROBLEM , AS HE TRAVELS ALOT VIA TRAINS & BUYS TICKET DIRECTLY AT STATION,
HIS ADVICE & PROBLEMS HE FACED AT STATION I CAN SOLVE .
PROBLEMS RELATED TO TICKET , FOOD , TIMING , INEFFICIENCY , LESS STAFF , ETC

****
     RECORD CALL WITH HIM , TELL HIM THAT I WILL RECORD A CALL AND ASK HIM CLEARLY AND ASK ABOUT THE THINGS WHICH HE THINKS ARE PROBLEM
     TELL HIM THAT I AM WORKING ON PROJECT , I WANT ALL THE INFO ABOUT THE STATE OF STATION & POTENTIAL PROBLEMS WHICH I CAN SOLVE USING ML VIA LLM 
****

****
    COMPARE PROBLEMS ACCORDING TO DYNANESH TO PROBLEMS FACED BY PAPPA , YOUNGSTERS VS OLD PEOPLE
****

### - refer recorded video of dynanesh , main points of video
  
     1. i asked him , "what is the problem statement , i mean how did you know this is the problem , i mean it would had clicked in your mind that yes this is 
        problem and it troubles some = kind of people ?
        reply = first of all , it is crowded , takes alot of time to get ticket from ticket counter , as at this machine we have alot of people , 
                basically problem can be solved by adding more machines, and there is only one machine( we don't know the name of machine) and also TC is 
                standing side of the machine , TC takes notes(money) from people and types somethings in machine i.e press some 10-20 buttons and we get ticket,
                basically this machine is complex ( for general passenger to see and understand as dynanesh said it is complex in a way that it seems he found 
                this machine complex )

( i researched and found out the name for machine is ATVM , confirmed with dynanesh ,)
 task :- found out how ATVM works , its features like --> 
                       book journey ticket : options 
                            using MAP
                            fast Booking
                            All other Stations
                            Check Train Availability
     use this knowledge of features of ATVM for building our product )

researched more = difference between ATVM & OCR kiosks machines
  ATVM = self-service , to buy tickets , so reduced traffic at ticket counter 
  ( as per dynanesh, TCs are present to give ticket i.e use machine for them )
  OCR kiosks machine = self-service machine for passengers to print their booked ticket
  ( aksh helped me with name of OCR machine ,  but he & i both were not sure of machine)

 my chat with Bing Chat GPT :- [Chat](https://github.com/Abhishekvidhate/LLM_problems/blob/main/chat-ATVM-OCRkiosks.docx) 

chat on intial product , basically a chat-bot (**using LLM for NLP**) for improving and simplifying UE of ATVM :-   [Chat](https://github.com/Abhishekvidhate/LLM_problems/blob/main/initial-product-chat.docx) 


### code base of ATVM machine 
info on CODE-BASE of ATVM(software & hardware info) : [thinvent.in](https://www.thinvent.in/railways/projects/atvm/) 

<details>
  <summary>
    how to integrate chat-bot with ATVM
  </summary>
  Copilot
Integrating your product with Automatic Ticket Vending Machines (ATVMs) involves several steps to ensure seamless functionality. Here’s a guide on how to proceed:

Understand ATVM Architecture:
Familiarize yourself with the existing ATVM system architecture.
Learn about the hardware components, communication protocols, and software interfaces used by ATVMs.
Identify Integration Points:
Determine where your product can fit into the ATVM workflow.
Common integration points include:
User Interface (UI): Enhance the existing touch-screen interface or add voice-based interactions.
Transaction Flow: Integrate your product into the ticket purchase process.
Smart Card Handling: If your product interacts with smart cards, ensure compatibility.
Choose the Integration Approach:
Depending on your product’s capabilities, choose an appropriate integration method:
API Integration: If the ATVM system provides APIs, use them to communicate with your product.
Middleware: Develop middleware that bridges communication between your product and the ATVM.
Hardware Integration: If your product requires additional hardware (e.g., voice modules), ensure compatibility.
Develop and Test:
Build the necessary components for integration:
User Interface: Design an intuitive UI that seamlessly integrates with the existing ATVM interface.
Communication Layer: Implement communication protocols (e.g., REST, MQTT) to exchange data between your product and the ATVM.
Smart Card Handling: If your product interacts with smart cards, develop the necessary drivers.
Rigorously test your integration in a controlled environment.
Security and Authentication:
Ensure that your product adheres to security standards.
Authenticate communication between your product and the ATVM to prevent unauthorized access.
Localization and Multilingual Support:
If your product supports multiple languages, ensure it aligns with the ATVM’s tri-lingual menu options1.
Consider localization for regional languages.
User Experience Enhancement:
Focus on improving the overall user experience:
Voice Interaction: If your product includes voice-based features, test them thoroughly.
Error Handling: Handle exceptions gracefully and provide clear instructions to users.
Deployment and Maintenance:
Deploy your integrated product to ATVMs in real-world scenarios.
Monitor performance, collect user feedback, and address any issues promptly.
Collaborate with Indian Railways:
Work closely with Indian Railways authorities to ensure compliance and alignment with their guidelines.
Seek approvals for deploying your product on ATVMs.
Documentation and Support:
Create detailed documentation for maintenance and troubleshooting.
Provide customer support for users interacting with your integrated product.
Remember that integrating with ATVMs requires thorough understanding, collaboration, and adherence to standards. Best of luck with your product integration! 🚂🎫✨

Learn more

1.thinvent.in
2.lipi.in
3.addsofttech.com
</details>

## 3. fruits vending machine , on roads , bus stands , train stands , etc 

## 4.
