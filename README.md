[Go Back](https://hs86442.github.io/)
# |
## Website 
# |
<!DOCTYPE html>
<html>
  <head>
    <title>First Website</title>
  </head>
  <body>
    <p>
      paragraph of text
    </p>

    <button>
      Hello
    </button>

    <a href="https://www.youtube.com/" target="blank">
      Link to YouTube
    </a>
  </body>
</html>

# |
## Buttons
# |
<title>buttons are here</title>
<style>
  .subscribe-button {
    background-color: rgb(200, 0, 0);
    color: white;
    border: none;
    border-radius: 2px;
    cursor: pointer;
    margin-right: 8px;
    margin-left: 20px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 16px;
    padding-right: 16px;
    transition: opacity 0.15s;
    vertical-align: top;
  }

  .subscribe-button:hover {
    opacity: 0.8;
  }

  .subscribe-button:active {
    opacity: 0.5;
  }

  .join-button {
    background-color: white;
    border-color: rgb(6, 95, 212);
    border-style: solid;
    border-width: 1px;
    color: rgb(6, 95, 212);
    border-radius: 2px;
    cursor: pointer;
    padding-top: 9px;
    padding-bottom: 9px;
    padding-left: 16px;
    padding-right: 16px;

    transition: background-color 0.15s,
      color 0.15s;
  }

  .join-button:hover {
    background-color: rgb(6, 95, 212);
    color: white;
  }

  .join-button:active {
    opacity: 0.7;
  }

  .tweet-button {
    background-color: rgb(29, 155, 240);
    color: white;
    border: none;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 16px;
    padding-right: 16px;
    border-radius: 8px;
    border-radius: 18px;
    font-weight: bold;
    font-size: 15px;
    cursor: pointer;
    margin-left: 8px;
    transition: box-shadow 0.15s;
    vertical-align: top;
  }

  .tweet-button:hover {
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.15);
  }
</style>

<button class="subscribe-button">
  SUBSCRIBE
</button>

<button class="join-button">
  JOIN
</button>

<button class="tweet-button">
  Tweet
</button>

# |
## Text
# |
<title>titles are defintately not here</title>
<style>
    p {
      font-family: Arial;
      margin-top: 0;
      margin-bottom: 0;
    }
  
    .video-stats {
      font-size: 14px;
      color: rgb(96, 96, 96);
      margin-bottom: 20px;
    }
  
    .video-title {
      font-weight: bold;
      font-size: 18px;
      width: 280px;
      line-height: 24px;
      margin-bottom: 5px;
    }
  
    .video-author {
      font-size: 14px;
      color: rgb(96, 96, 96);
      margin-bottom: 20px;
    }
  
    .video-description {
      font-size: 14px;
      color: rgb(96, 96, 96);
      width: 280px;
      line-height: 22px;
      margin-bottom: 100px;
    }
  
    .apple-text {
      margin-bottom: 50px;
      font-size: 14px;
      background-color: rgb(227, 65, 64);
      color: white;
      text-align: center;
      padding-top: 18px;
      padding-bottom: 18px;
    }
  
    .span-example {
      color: red;
    }
  
    .span-example:hover {
      text-decoration: underline;
    }
  
    .shop-link {
      cursor: pointer;
    }
  
    .shop-link:hover {
      text-decoration: underline;
    }
  </style>
  
  <p class="video-title">
    Talking Tech and AI with Google CEO Sundar Pichai!
  </p>
  
  <p class="video-stats">
    3.4M views &#183; 6 months ago
  </p>
  
  <p class="video-author">
    Marques Brownlee &#10003;
  </p>
  
  <p class="video-description">
    Talking tech and AI on the heels of Google I/O. Also a daily driver phone reveal from Google's CEO. Shoutout to Sundar!
  </p>
  
  <p class="apple-text">
    Shop early for the best selection of holiday favourites. <span class="shop-link">Shop now &#62;</span>
  </p>
  
  <p>
    Shop early for the <strong>best selection</strong> of <u>holiday</u> favourites. <span class="span-example">Shop now</span>
  </p>
