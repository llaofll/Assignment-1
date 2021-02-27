*** Settings ***
Library  SeleniumLibrary
*** Variables ***
${HOMEPAGE}  http://www.youtube.com
${BROWSER}  chrome
*** Test Cases ***
Go To homepage
  Open Browser  ${HOMEPAGE}  ${BROWSER}