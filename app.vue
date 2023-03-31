<template>
  <div class='body'>
    <div class='header'>
      <h1>Adrian Wilfred LeBlanc</h1>
    </div>

    <div class='carousel'>
      <div class='carousel_cards'>
        <img class='card' src="/images/sunnies.jpg">
        <img class='card' src="/images/helmet.jpg">
        <img class='card' src="/images/window.jpg">
        <img class='card' src="/images/sunnies.jpg">
        <img class='card' src="/images/helmet.jpg">
        <img class='card' src="/images/window.jpg">
      </div>

      <div class='carousel_cards'>
        <img class='card' src="/images/sunnies.jpg">
        <img class='card' src="/images/helmet.jpg">
        <img class='card' src="/images/window.jpg">
        <img class='card' src="/images/sunnies.jpg">
        <img class='card' src="/images/helmet.jpg">
        <img class='card' src="/images/window.jpg">
      </div>

    </div>

    <div class='text_content'>
      <p>
        On November 9, 2022, a gem of a son, brother and fiancé passed away peacefully at home, in his childhood bedroom, surrounded by all his loved ones.
      </p>
      <p>
        Having survived cancer as an infant, Adrian grew up with regular hospital visits at CHEO.  In spite of, or because of this, he lived his 27 years to the fullest.  He graduated from Algonquin College with a Civil Engineering Technology Diploma.  He started working for IBI Group in 2017 until cancer caught up with him again.
      </p>
      <p>
        Adrian was born in the Philippines on January 03, 1995 to Thomas and Malou LeBlanc. The family moved to Kemptville in 1998 and has since called it home.  Most summers were spent in Nova Scotia, where he spent time either visiting with family in the ancestral home, or on the beach, swimming, making campfires and riding four-wheelers, or out in the ocean deep sea fishing, and of course, eating lobsters and rappie pie.  Visits to the Philippines were few but were thoroughly enjoyed by him. He was looking forward to going back one day, to visit his maternal grandparents.
      </p>
      <p>
        Growing up, Adrian's charismatic personality touched the lives of many of his classmates, neighbours, acquaintances and co-workers of all ages, resulting in a diverse, compassionate group of friends. He enjoyed spending time with them either gaming online, playing board games, going out, hunched under the hood of his car in the garage or even just talking over the phone.
      </p>
      <p>
        Family was foremost in his heart and mind.  He loved spending time with them either just hanging out at home, cooking his favourite Filipino dishes or going on trips.  Not to forget the family pet, “Amy the dog,” with whom he found comfort during his treatments.
      </p>
      <p>
        In the last years of his life, his commitment to his loving fiancée was a priority.  They were planning a life of their own, no matter what.  Second to this was his passion for his car – tinkering, learning about and fixing every aspect of it, from the mechanical to the electrical components. Despite his compromised and declining health, he was able to drive this car, which he spent numerous hours on, for two seasons on the Circuit Mont-Tremblant race track.
      </p>
      <p>
        In addition to his car obsession, he loved snowboarding and riding his motorcycle when he could.  He collected wrist watches of all types, and could talk about the mechanics of clockwork with much enthusiasm.
      </p>
      <p>
        Adrian leaves behind his parents Thomas and Malou, brother Brian, sister Alicia (Kieran) and fiancée Kelly.  He is also survived by grandparents Edgardo and Yolanda Paglinawan, Philippines, a host of beloved aunts, uncles and cousins from both sides of the world.  He will be greatly missed by friends and neighbours whose lives he touched.  He is predeceased by grandfather Wilfred LeBlanc and grandmother Célina LeBlanc.
      </p>
      <p>
        A Funeral Mass was held at Holy Cross Church, 502 Clothier Street West, Kemptville on Monday, November 21st at 11 am, officiated by Rev. Raymond de Souza.  Reception followed in the parish hall.
      </p>
    </div>
    <div class='footer'></div>
  </div>
</template>

<style lang='scss'>
$carousel_height: 300px;
$image_width: 500px;

body {
  overflow-x: hidden;
  overflow-y: scroll;
  margin: 0;
  padding: 0;
  width: 100%;
  display: flex;
  flex-direction: row;
  text-align: center;
  align-items: center;
  color: white;
  background: linear-gradient(180deg, rgb(0, 0, 0) 0%, rgb(102, 102, 102) 100%);

  .header {
    padding: 0 3vw 0 3vw;
    h1 {
      margin-top: 3vw;
      font-size: calc(2rem + 3vw);
    }
  }

  .text_content {
    padding: 0 3vw 0 3vw;
    font-size: calc(1rem + 0.5vw);
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  }

  .footer {
    background-color: black;
    height: 50px;
  }

  .carousel {
    padding: 20px 0 20px 0;
    overflow: hidden;
    width: 99vw;
    margin: 0 auto;
    position: relative;
    display: flex;

    .carousel_cards {
      display: flex;
      position: relative;
      animation: marquee 100s linear infinite;
      justify-content: space-around;
    }

    .card {
      display: block;
      min-width: 500px;
      height: 300px;
      margin: 0 1vw;
      object-fit: cover;
      border-radius: 50px;
      box-shadow: -2px 5px 10px 6px rgba(0,0,0,0.35);
    }

    @keyframes marquee {
      0%   { transform: translateX(0%); }
      100% { transform: translateX(-100%); }
    }
  }
}
</style>