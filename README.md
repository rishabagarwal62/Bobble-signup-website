# Bobble-signup-website

The page was made using HTML, CSS and JAVAscript

# A Signup Page

# For integrating Google Api, the documentation was followed and the below codes were used

<!--Google Platform Library-->
        <script src="https://apis.google.com/js/platform.js" async defer></script>

<!--To Specify Client ID-->
        <meta name="google-signin-client_id" content="235481241571-le55mbm5o5q2efbo2rnv5puo57lpu14u.apps.googleusercontent.com.apps.googleusercontent.com">
                   
# For integrating Facebook JavaScript SDK

    <div id="fb-root"></div>
    <script async defer crossorigin="anonymous" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&version=v8.0&appId=380110219828582&autoLogAppEvents=1" nonce="LdDEJ7i1"></script>
    
# ForSetting Up the Facebook SDK for Javascript

<script>
    window.fbAsyncInit = function() {
      FB.init({
        appId      : '258718028843750',
        cookie     : true,
        xfbml      : true,
        version    : 'v8.0'
      });
        
      FB.AppEvents.logPageView();   
        
    };
  
    (function(d, s, id){
       var js, fjs = d.getElementsByTagName(s)[0];
       if (d.getElementById(id)) {return;}
       js = d.createElement(s); js.id = id;
       js.src = "https://connect.facebook.net/en_US/sdk.js";
       fjs.parentNode.insertBefore(js, fjs);
     }(document, 'script', 'facebook-jssdk'));
  </script>
  
# For Facebook Plugin to appear

            <div class="fb-login-button" data-size="large" data-button-type="login_with" data-layout="default" data-auto-logout-link="false" data-use-continue-as="false" data-width=""></div>

# For Google Plugin to appear

            <div class="g-signin2" data-onsuccess="onSignIn"></div>
  
  
        
