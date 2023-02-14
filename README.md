<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
 
<h3 align="center">Sample API</h3>

  <p align="center">
    These is example APIs, for study purposes in go lang network and distributed services.
    <br />
  </p>
</div>









<!-- GETTING STARTED -->
## Getting Started

Clone the project & setup GOLang

* Terminal
  ```
  go run main.go
  ```


* Terminal
  ```
  curl -X POST localhost:8080 -d \
    '{"record": {"value": "TGV0J3MgR28gIzEK"}}'
  ```
  
 * Terminal
  ```
  curl -X POST localhost:8080 -d \
    '{"record": {"value": "TGV0J3MgR28gIzIK"}}'
  ```
  
  * Terminal
  ```
  curl -X POST localhost:8080 -d \
    '{"record": {"value": "TGV0J3MgR28gIzMK"}}'
  ```
  
  
   * Terminal
  ```
  curl -X GET localhost:8080 -d '{"offset": 0}'
  ```
  
  
   * Terminal
  ```
curl -X GET localhost:8080 -d '{"offset": 1}'
  ```
  
  
   * Terminal
  ```
 curl -X GET localhost:8080 -d '{"offset": 2}'
  ```
