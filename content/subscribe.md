---
title: "Subscribe to Words by Design"
layout: "single"
url: "/subscribe/"
summary: Subscribe to Words by Design and get new posts directly in your inbox.
---
<head>
<style> 
      input[type="email"],
      input[type="text"],
      input[type="checkbox"],
      /*input[type="submit"],*/
      textarea {
        border: 2px solid #9b59b6;
        padding: 16px;
        outline: none;
        color: #9b59b6;
        border-radius: 6px;
        /* border-bottom: 1px solid #000; /* You can adjust the color and thickness of the outline */
      }
      input[type="submit"],
      textarea {
        padding: 16px;
        color:  #f4ecf7;
        background: #9b59b6;
        font-weight: bold;
        border-radius: 6px;
      }
    </style>
</head>
<body>
<form method="post" action="https://wbd.pikapod.net/subscription/form" class="listmonk-form">
    <div>
        <!--<h3>Subscribe</h3>-->
        A UX content designer's learnings and musings. Get new posts directly to your inbox.
        <p></p>
        <input type="hidden" name="nonce" />
        <label for="email"><strong>EMAIL</strong></label>
        <p><input type="email" name="email" required placeholder="cool_email@domain.com" /></p>
        <label for="name"><strong>NAME (optional)</strong></label>
          <p><input type="text" name="name" placeholder="Cool Name" /></p>
        <label for="1"><strong>NEWSLETTER</strong></label>
        <p><input id="d807c" type="checkbox" name="l" checked value="d807ce2f-699a-498a-a51f-e8d89c99a51c" />
          <label for="d807c">Words by Design</label><br /><!--<span>A UX content designer's exploration of topics related to UX. Resources will also be shared so we can learn together.</span>-->
        </p>
        <p><input type="submit" value="Subscribe" /></p>
        <p style="font-size: small"><em>You can unsubscribe at any time</em></p>
    </div>
</form>
</body>