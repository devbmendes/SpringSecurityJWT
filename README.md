# Spring Security whith JWT - Jason Web Token
<p> Security is a must when designing and building API and it is a really important to understand Spring Security and JWT so that you can secure your API <p/>
<h3> When should you use JSON Web Tokens? </h3>
<h3> Authorization:</h3>
 <p>
   This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, 
   services, and resources that are permitted with that token. Single Sign On is a feature that widely uses JWT nowadays, because of its small 
   overhead and its ability to be easily used across different domains.
  <p/>

<h3>
  Information Exchange:
 </h3>
  <p>
    JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, 
    using public/private key pairs—you can be sure the senders are who they say they are. Additionally, as the signature is calculated using the header 
    and the payload, you can also verify that the content hasn't been tampered with.
   </p>
<h3>
 How it works
 </h3>
 <div align="center">
 <img height="300px" width="800px" center src="https://github.com/devbmendes/SpringSecurityJWT/assets/57733068/b44116cb-f040-416c-b68b-ee788b249d84" />
 </div>

