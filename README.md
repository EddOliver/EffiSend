[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [<img src="https://img.shields.io/badge/View-Website-blue">](https://kharonprotocol.com) [<img src="https://img.shields.io/badge/View-Video-red">](https://www.youtube.com/watch?v=Fiele_PBU-0)


# EffiSend

<img src="https://i.ibb.co/QmMQvJv/images.png" width="300">

Welcome, this is our project for Celo’s Mobile online Hackathon.

Because of the size it is in an AWS bucket.
### APK: https://general-bucket-android.s3.amazonaws.com/app-debug.apk

Login:

- User: celouser@gmail.com 
- Pass: toor

Here is our main demo video: 

[![Demo](https://i.ibb.co/g4W3ypx/image.png)](FALTA EL LINK DEL VIDEO)

# Introduction and Problem

Almost 4 years ago Vitalik Buterin, co founder of Ethereum posted in twitter this message:

<img src="https://i.ibb.co/ggfZWPD/vitalik.png">

At that time it grabbed the attention of almost the entire crypto space and the answers regarding that question were mostly a big “Not many if at all”. Of course there have been isolated projects that try to work with the developed world with several big names attached , but not to much avail. Cryptocurrencies and blockchain technology from that time onwards has mostly been used by a few early adopters and some others, but were mostly already banked, educated people, even in the developing world. 

Now, let’s ask that same question today; How many unbanked have we banked by the year 2021? Despite having made great progress and having outliers like the country of El Salvador, outside of that, the progress is almost null. Most of the same people that are into crypto today have been in for years and are the same elite, educated, previously banked ones, it has not reached those who are not.   

We can say that because our team lives in one of those developing countries that countless projects try to portray as a target for financial inclusion. 

And yes Mexico is the perfect target as it is the largest issuer of remittances from the US and it will break $42Billion this year alone.  

<img src="https://cdn.howmuch.net/articles/outgoing-remittances-usa-final-8374.jpg">


Of course, remembering that the US is the biggest sender of remittances in the world.

It is important to mention that, according to the World Bank, 65% of Mexican adults do not have any type of bank account and only 10% save through a financial institution, in addition to the fact that 83% of Mexican adults do not have access to electronic payment systems. These circumstances limit the potential of the sector to place the resources of savers in productive projects that generate economic development and well-being for the population. And crypto is not doing better than the legacy system, most of the users are people like our team, tech savvy with a certain degree of education and already banked.

Now let’s review a bit the CELO ecosystem. The concept to reach the unbanked via substituting the crypto address with the phone number is powerful. That has great potential as most of the population here, even unbanked, has a cellphone this number reaching almost 76% of the population.

<img src="https://i.ibb.co/Qmx97cr/valora.png">

When we went deeped our research we analyzed  the Valora wallet and application. Despite its great potential and a la Venmo but for crypto transfer capabilities we found great problems with its Cash Out portion. Xbox, Uber, google play and cell phone payments? Sorry for being aggressive, but this does not work for that unbanked population in any way, this is more for the “already banked” elite populace. Most remittances are done electronically yes, but through services like Western union where the families can get cash. This will never talk to them. 

But I think that with certain systems that are already in place and the great potential of CELO we can produce a Dapp that does that cashout part correctly, directed at that populace, and improve on financial inclusion.



# Solution

Effisend is a CELO based mobile DApp that improves Cash out processes and integrates it with Rapyd (biggest payment processor in the world) to improve financial inclusion in Mexico.

System's Architecture:

<img src="https://i.ibb.co/xCr1qDm/Untitled-Diagram-drawio.png">

App Screens:

Thanks to the Rapyd APIs we can manage users, such as registration, login and KYC of our app.

<img src="https://i.ibb.co/BBWQ33m/Screenshot-1638060296.png">

- In turn, through Rapyd and CELO we can have total control of the movements and transactions of our account in both Crypto and Fiat.

- All CELO transactions are controlled through an express server on AWS with the Celo CLI interface.

- We carry out Celo and Fiat transfers by coordinating the services of Celo and Rapyd. Transferring the equivalent of CELO or US Dollar from EffiSend Master accounts.

<img src="https://i.ibb.co/kBZwZ0d/Screenshot-1638060296-1.png">

- At the same time, we can obtain a virtual card from the Rapyd API to be able to spend the money from our Fiat account directly.

- Above all, we can make a SPEI transfer from our Fiat account to a bank account or Saldazo® or SPIN debit cards.

- All transfers made in the demos and during development can be consulted in the explorer.

https://alfajores-blockscout.celo-testnet.org/address/0xE7c1fc2B18A0Ee4F087694bca90436Eba6f16Fca/token-transfers

<img src="https://i.ibb.co/KqGVq5v/Screenshot-1638060296-2.png">

- And in turn we show a screenshot of our backend in Rapyd.

<img src="https://i.ibb.co/cFX3NYb/Screenshot-from-2021-11-27-19-12-24.png">

Uncut, unedited demo:

Video: Click on the image
[![Demo](https://i.ibb.co/g4W3ypx/image.png)](https://youtu.be/Kue85N-CO2Q)

Sorry github does not allow embed videos.

# What's next for Effisend

We 

# Team

#### 3 Engineers with experience developing IoT and hardware solutions. We have been working together now for 5 years since University.

[<img src="https://img.shields.io/badge/Luis%20Eduardo-Arevalo%20Oliver-blue">](https://www.linkedin.com/in/luis-eduardo-arevalo-oliver-989703122/)

[<img src="https://img.shields.io/badge/Victor%20Alonso-Altamirano%20Izquierdo-lightgrey">](https://www.linkedin.com/in/alejandro-s%C3%A1nchez-guti%C3%A9rrez-11105a157/)

[<img src="https://img.shields.io/badge/Alejandro-Sanchez%20Gutierrez-red">](https://www.linkedin.com/in/victor-alonso-altamirano-izquierdo-311437137/)


Linkos

https://egade.tec.mx/es/egade-ideas/opinion/la-inclusion-financiera-en-mexico-retos-y-oportunidades


(https://www.cnbv.gob.mx/Inclusi%C3%B3n/Anexos%20Inclusin%20Financiera/Panorama_IF_2021.pdf?utm_source=Panorama&utm_medium=email)


https://www.inegi.org.mx/contenidos/saladeprensa/boletines/2021/OtrTemEcon/ENDUTIH_2020.pdf

(https://www.cnbv.gob.mx/Inclusi%C3%B3n/Anexos%20Inclusin%20Financiera/Panorama_IF_2021.pdf?utm_source=Panorama&utm_medium=email)



