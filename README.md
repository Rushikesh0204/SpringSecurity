# SpringSecurity
8) Spring Security :
  -SS is a application security framework provide appliction lavel security
  -like login logout functionality
  - allow / block access to URL to logged in user and also certain roels (admin ,un resister user)
    
* why ss:
  -Handles commen vulnerability - session fixation ,clickjacking,click site request forgery
  -widely adopted
* what ss do
  -user name ,password authentication
  -application level authorization
  -intra application autherization like OAuth
  -Microservice security (using token JWT)
  -method level security
  
  <h4>core concept in spring security</h4>
  
a) Authentication and Authorization - Authentication : ask two question -1 who r u , 2 prove * * thise authentication known as knowledge based authentication -(stored user ID ,PASS) -

Advantage- easy way to implement -

DisAdvantage - if some one has a pass then he can access

b) Possession based authenrication :
