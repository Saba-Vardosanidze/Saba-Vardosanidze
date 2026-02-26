<div align="center">
  <style>
    .typing-container {
      display: inline-block;
      text-align: center;
      width: 100%;
    }
    
    .type-title {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid #22c55e;
      width: 0;
      margin: 0 auto 10px auto;
      animation: typing 1.5s steps(30, end) forwards, blinkTitle 0.7s step-end infinite;
    }
    
    .type-text {
      overflow: hidden;
      white-space: nowrap;
      border-right: 3px solid transparent;
      width: 0;
      margin: 3px auto;
      font-size: 16px;
    }

    /* პირველი ხაზის ანიმაცია */
    .line1 {
      animation: typing 1.2s steps(40, end) 1.5s forwards, blinkLine 0.7s step-end 1.5s 2;
    }

    /* მეორე ხაზის ანიმაცია (იწყება პირველის დასრულებისას) */
    .line2 {
      animation: typing 1.2s steps(40, end) 2.7s forwards, blinkLine 0.7s step-end infinite 2.7s;
    }

    .fade-in-btn {
      opacity: 0;
      display: inline-block;
      margin-top: 15px;
      animation: fadeIn 1s ease 4s forwards;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blinkTitle {
      from, to { border-color: transparent; }
      50% { border-color: #22c55e; }
    }

    @keyframes blinkLine {
      from, to { border-color: transparent; }
      50% { border-color: #555; }
    }

    @keyframes fadeIn {
      to { opacity: 1; }
    }

  </style>

  <table width="100%" style="table-layout: fixed;">
    <tr>
      <td width="50%" align="center" valign="middle">
        <video 
            src="./vardosanidze.mp4" 
            autoplay 
            loop 
            muted 
            playsinline 
            width="100%" 
            style="border-radius: 12px;">
        </video>      
      </td>
      <td width="50%" align="center" valign="middle">
        <div class="typing-container">
          <h2 class="type-title">
            Hello, I’m Saba
            <img src="./Neko Gojo Satoru.gif" alt="👋" style="width:32px; height:32px; vertical-align:middle; margin-left: 8px;">
          </h2>
          <p class="type-text line1">This is my digital world. Explore my projects,</p>
          <p class="type-text line2">experience, and tech insights in one place.</p>
        </div>
        <br>
        <a href="https://www.vardosanidze.online/" class="fade-in-btn">
          <img src="https://img.shields.io/badge/View_Portfolio-22c55e?style=for-the-badge&logo=react&logoColor=white" alt="Portfolio" />
        </a>
      </td>
    </tr>
  </table>
</div>
