Rest API
=======

This API helps to perform Lucas series, Fibonacci series and factorial for a number. 

Usage
-----

#### Lucas Series ####

##### API Call #####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/lucas/<int:number>
```
##### Parameters #####
number : number is of int data type

##### API Call example #####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/lucas/5
```

##### API Response #####
```Result
HTTP/1.0 200 OK
Content-Type: application/json
Content-Length: 27
Server: Werkzeug/0.11.11 Python/2.7.12
Date: Wed, 09 Nov 2016 02:43:41 GMT

{"lucas": "2, 1, 3, 4, 7"}


```
The output is in json data format
#### Fibonacci Series ####

##### API Call#####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/fibonacci/<int:number>
```

##### Parameters #####
number : number is of int data type

##### API Call example #####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/fibonacci/5
```
##### API Response#####
```Result
HTTP/1.0 200 OK
Content-Type: application/json
Content-Length: 31
Server: Werkzeug/0.11.11 Python/2.7.12
Date: Wed, 09 Nov 2016 02:44:45 GMT

{"fibonacci": "0, 1, 1, 2, 3"}

```
The output is in json data format
#### Factorial ####

##### API Call#####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/fact/<int:number>
```
##### Parameters #####
number : number is of int data type

##### API call Example #####
```API
http://ec2-52-37-54-12.us-west-2.compute.amazonaws.com/fact/5
```
##### API Response#####
```Result
HTTP/1.0 200 OK
Content-Type: application/json
Content-Length: 19
Server: Werkzeug/0.11.11 Python/2.7.12
Date: Wed, 09 Nov 2016 02:45:40 GMT

{"factorial": 120}

```
The output is in json data format
