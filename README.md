# [Natas](http://overthewire.org/wargames/natas/) Log

Natas teaches the basics of serverside web-security.

## Level 1

Hidden in commented out code
FLAG: gtVrDuiDfck831PqWsLEZy5gyDz1clto

## Level 2

Same story, but right clicking was blocked

FLAG: ZluruAthQk7Q2MqmDeTiUij2ZvWy2mBi

## Level 3

There was nothing on that page, but /files was left unsecured and has a list of usernames and passwords

FLAG: sJIJNW6ucpu6HPZ1ZAchaDtwd7oGrD14

## Level 4

FLAG: Z9tkRkWmpt9Qr7XrR5jWRkgOU901swEZ

The robots.txt was disallowing a directory called /s3cr3t/, which is where this was

## Level 5

Access disallowed. You are visiting from "http://natas4.natas.labs.overthewire.org/index.php" while authorized users should come only from "http://natas5.natas.labs.overthewire.org/" 

FLAG: iX6IOfmpN7AYOQGPwtn3fXpbaJVJcHfq

I used a header editing extension in Chrome to spoof the header. Interestingly, it seems that Firefox's 'edit headers and resend' util doesn't allow you to spoof the referrer.

Some people use Burp for this, but I'm sticking to my guns and not installing fancy tools that I don't understand yet.

## Level 6

FLAG: aGoY4q2Dc6MgDq4oL4YtoKtyAg9PeHa1

Fiddled with a cookie value

## Level 7

FLAG: 7z3hEENjQtflzgnT29q7wAvMNfZdh0i9

Hints in the code led me to an insecure file

## Level 8

FLAG: DBfUBfqQG69KvJvJ1iAbMoIpwSNQ9bWe

Reflection attack


## Level 9

FLAG: W0mMhUcRRnG8dcghE4qvk3JA9lGt8nDl

Reverse engineering an insecure password encoding function


## Level 10

FLAG: nOpp1igQAkUzaI1GUUjzn1bFVj7xCNzu

Inputs not sanitized


## Level 11

FLAG: U82q5TCMMQ9xuFoI3dYX61s7OZD9JKoK

Inputs similarly not sanitized. Not super enjoying this because it involves learning some PHP and I cant' be bothered.
