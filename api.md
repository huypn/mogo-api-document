FORMAT: 1A
HOST: http://dev.mogoapp.co/api

# Mogo API

## Authorization
API will require the `X-Auth-Token` HTTP header.

```http
X-Auth-Token: vr5HmMkzlxKE70W1y4MibiJUusZwZC25NOVBEx3BD1
```

# Group Users

## Login with Email [/login] 

### Post Login with Email [POST]

+ Request (application/json)

      + Body

            {
                "email": "example@gmail.com",
                "password": "123456",
                "deviceToken": ""
            }

    
+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Logout [/logout] 

### Post Logout [POST]

+ Request

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

+ Response 200 (application/json)

        {
            "message": {
                "type": "success",
                "code": 1000,
                "msg": "Success"
            }
        }

## Login with Facebook [/login/facebook] 

### Post Login with Facebook [POST]

+ Request (application/json)

      + Body

            {
                "token": "EAAJCKYTYO1QBAJMRoZBzJYr6ZC54mDNFDrOwOOLYB0j4HtlUTLZA7Rhc3DQ93XmUvo2VcKgSZCxD5GP4iScW7aoi8zpjLQRZArmggQ9rmDr9MUkNHNvuThgMAM77lfLajZAZBnKCGTM0MGboDIhs0msBPrDvgkM86rreKZBCi4uAuGFjTLtrgfZBK",
                "deviceToken": ""
            }

+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Login with Google [/login/google] 

### Post Login with Google [POST]

+ Request (application/json)

      + Body

            {
                "token": "eyJhbGciOiJSUzI1NiIsImtpZCI6ImRlOTdmMzA1MTRjOWU4NThiYzA0ODc3NjNmNzNmN2UwYzVmYTBhYjEifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJpYXQiOjE0ODY5NTczODMsImV4cCI6MTQ4Njk2MDk4MywiYXRfaGFzaCI6ImdaNU03bVlhbnVFd2xxN2w1ZFY1Q2ciLCJhdWQiOiIzODMyODYxNzU2NC04b2g1YTRqZWplYnNvZzgwamh1bHJpcGk5NzVlYXM5ZC5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjEwNDk4MzA4OTI1OTY5NDE1NTk5OSIsImVtYWlsX3ZlcmlmaWVkIjp0cnVlLCJhenAiOiIzODMyODYxNzU2NC04b2g1YTRqZWplYnNvZzgwamh1bHJpcGk5NzVlYXM5ZC5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsImhkIjoiaHV5cGhhbS5pbyIsImVtYWlsIjoiY29udGFjdEBodXlwaGFtLmlvIiwibmFtZSI6Ikh1eSBQaGFtIiwicGljdHVyZSI6Imh0dHBzOi8vbGg0Lmdvb2dsZXVzZXJjb250ZW50LmNvbS8tNVdsNEt0SjVtVUUvQUFBQUFBQUFBQUkvQUFBQUFBQUFBb2MveWRBYzRXVEF6em8vczk2LWMvcGhvdG8uanBnIiwiZ2l2ZW5fbmFtZSI6Ikh1eSIsImZhbWlseV9uYW1lIjoiUGhhbSIsImxvY2FsZSI6ImVuIn0.QnDPlixGuNp4cCe57Li8_tSDixEcemSgyzmdR-tZVL8kTRajajQZ1KVDkW9KpdB6y2x88SCSbA1tJlJuTN8v052i69pkqnwVg43hU6h--m4I4SFoRT3St3ff_bvyUZd_pP4v2jrzK1dbauh2RoP5x-qhidGuFM52PIryXBfC69zWsLzILHbosSTS0WCxTgUJ7SeHpf58ivrkc72ZPNUvyw1GbbjqLICphJYANzYsr43xnoIzU2_izanXY07pwsVmZFWjOJhTc7X3xnIyfB9n64xVtPPSXF9IsgpHqYDKCQOTr7YBHPMmKmRTmJOixW0SAAHvJHz9AtKmntG-hKGLFQ",
                "deviceToken": ""
            }

+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }


## Login with Twitter [/login/twitter] 

### Post Login with Twitter [POST]

+ Request (application/json)

      + Body

            {
                "token": {
                    "oauth_token": "2956901154-SUSJUlJDvESbfd7UOqCVCAGHWxxYOzudgxTDGmc",
                    "oauth_token_secret": "H4hcgPWd9OKMJZ7XI7oXITMKZ4b1zRONzkQQkTE8bkVUG"
                },
              "email": "contact@huypham.io",
              "deviceToken": ""
            }

+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Social Connect [/login/connect]
Connect with current account

### Social Connect [POST]

+ Request (application/json)

	 + Body
	
				{
					"token": "",
					"email": "",
					"type": "facebook|google|twitter"
 	 			}
 	 			
+ Response 200 (application/json)

			{
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Social Disconnect [/login/disconnect]
Disconnect current account with social account

### Social Disconnect [POST]

+ Request (application/json)

	 + Body
	
				{
					"email": "",
					"type": "facebook|google|twitter"
 	 			}
 	 			
+ Response 200 (application/json)

			{
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }


## Register with Email [/register] 

### Post Register with Email [POST]

+ Request (multipart/form-data)

    + Body

            ------WebKitFormBoundary7MA4YWxkTrZu0gW
            Content-Disposition: form-data; name="file"; filename=""
            Content-Type: 


            ------WebKitFormBoundary7MA4YWxkTrZu0gW
            Content-Disposition: form-data; name="user"

            {"email": "hnmtuan3310@gmail.com", "fullname": "tuan hoang 3310", "plainPassword": "123456", "phone": "01674559825"}
            ------WebKitFormBoundary7MA4YWxkTrZu0gW--

    
+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Update Profile [/user/profile] 

### Post Update Profile [POST]

+ Request (multipart/form-data)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

    + Body

            ------WebKitFormBoundary7MA4YWxkTrZu0gW
            Content-Disposition: form-data; name="file"; filename=""
            Content-Type: 

            {"fullname": "tuan hoang 3310", "plainPassword": "123456", "notification_email": 1, "notification_sms" : 0, "notification_push" : 1}
            ------WebKitFormBoundary7MA4YWxkTrZu0gW--
    
+ Response 200 (application/json)

        {
            "data": [
                "id": 1,
                "fullname": "123",
                "email": "kennyfans999@gmail.com",
                "avatar": "http://mogo.dev/media/5880e8e0ca978.jpg",
                "phone": "01674559825",
                "notification_email": 0,
                "notification_sms": 0,
                "notification_push": 0,
                "facebook_connect": 0,
                "google_connect": 0,
                "twitter_connect": 0,
                "token": "1d2aa620d5750f7940b008143883f7d35849e373"            
            ]
        }

## Check email exist [/check-email] 

### Post Check email exist [POST]

+ Request (application/json)

    + Body

            {
                "email": "example@gmail.com"
            }

    
+ Response 200 (application/json)

        {
            "message": {
                "type": "success",
                "code": 1000,
                "msg": "You can use this email !"
            }
        }

+ Request (application/json)

    + Body

            {
                "email": "example@gmail.com"
            }


+ Response 200 (application/json)

        {
            "message": {
                "type": "error",
                "code": 1001,
                "msg": "Email already exist !"
            }
        }

## Check phone number exist [/check-phone] 

### Post Check phone number exist [POST]

+ Request (application/json)

    + Body

            {
                "phone": "090999999999"
            }

    
+ Response 200 (application/json)

        {
            "message": {
                "type": "success",
                "code": 1000,
                "msg": "You can use this phone number !"
            }
        }

+ Request (application/json)

    + Body

            {
                "phone": "090999999999"
            }


+ Response 200 (application/json)

        {
            "message": {
                "type": "error",
                "code": 1001,
                "msg": "Phone number already exist !"
            }
        }
## Forget Password [/forgot-password] 

### Request url to reset password [POST]

+ Request Success (application/json)

    + Body

            {
                "email": "email@gmail.com"
            }

    
+ Response 200 (application/json)

        {
            "message": {
                "type": "success",
                "code": 1000,
                "msg": "Success"
            }
        }

+ Request Error (application/json)

    + Body

            {
                "email": "email2@gmail.com"
            }


+ Response 200 (application/json)

        {
            "message": {
                "type": "error",
                "code": 1100,
                "msg": "Account does not exist"
            }
        }

## Request Verify Phone Code [/user/phone/request_code]

### Request Code [POST]

+ Request (application/json)

	+ Body
	
            {
                "email" : "",
                "phone": ""
            }
	 			
+ Response 200 (application/json)

			{
				"type": "success",
				"msg": "Success"
			}

## Verify Phone Code [/user/phone/verify_code]

### Verify Code [POST]

+ Request (application/json)

	+ Body
	
            {
                "email" : "",
                "phone": "",
                "code": ""
            }
	 			
+ Response 200 (application/json)

			{
				"type": "success",
				"msg": "Success"
			}

## Notification List [/notifications]

### Notification List [POST]

+ Request (application/json)

	+ Body
	
            {
                "page" : 1, // Optional
                "number": 10, // Optional
                "user_id": 3 // Required
            }
	 			
+ Response 200 (application/json)

			{
                "data": [
                    {
                        "title": "Animi commodi dolorum nihil voluptas odio aperiam non.",
                        "body": "Unde neque optio reiciendis dolores nulla in. Et accusamus et vel laudantium numquam. Ex fugiat fuga delectus rerum voluptates.",
                        "status": 0,
                        "created_at": null
                    }
                ],
                "meta": {
                    "pagination": {
                        "total": 1,
                        "count": 1,
                        "per_page": 10,
                        "current_page": 1,
                        "total_pages": 1,
                        "links": []
                    }
                },
                "message": {
                    "type": "success",
                    "code": 1000,
                    "msg": "Success"
                }
            }

# Group Places
Search and manage places.

## places List [/places{?people,sortBy,priceFrom,priceTo,rating,cuisine,hasDiscount,lat,long,number}]

### Get places List [GET]

+ Parameters

    + people (required, integer, `2`) ... Số lượng người
    + sortBy (required, string, `time`)
        + `time`
        + `price`
        + `localtion`
        + `favorite`
    + priceFrom (required, integer, `0`) 
    + priceTo (required, integer, `150000`)
    + rating (required, integer, `4`)
    + cuisine (required, integer, `1`)
    + hasDiscount (optional, integer, `1`)
    + lat (required, float, `10.747426`) ... Latitude của location hiện tại
    + long (required, float, `106.701245`) ... Longitude của location hiện tại
    + number = `20` (optional, integer, `25`) ... Số lượng nhà hàng muốn lấy


+ Response 200 (application/json)

        {
            "data": [
                {
                    "id": 11,
                    "name": "Ramiro",
                    "rating": 0,
                    "time_waiting": 900,
                    "latitude": "10.779011",
                    "longitude": "106.720009",
                    "discount": 5,
                    "distance": 4.07,
                    "categories" : {
                        "data" : [
                            {
                                "id" : 1,
                                "name" : Seafood
                            },
                            {
                                "id" : 2,
                                "name" : Beef
                            }
                        ]
                    }
                },
                {
                    "id": 80,
                    "name": "Elenora",
                    "rating": 0,
                    "time_waiting": 900,
                    "latitude": "10.710105",
                    "longitude": "106.715846",
                    "discount": 20,
                    "distance": 4.45,                    
                    "categories" : {
                        "data" : [
                            {
                                "id" : 1,
                                "name" : Seafood
                            },
                            {
                                "id" : 2,
                                "name" : Beef
                            }
                        ]
                    }
                },
            ]
        }

## places Detail [/places/{id}]
Manage an existing places.

+ Parameters

    + id (required, integer) ... The unique identifier of a place

### Get places Detail [GET]

+ Response 200 (application/json)

        {
            "data" : {
                "id": 2,
                "name": "Kielisski",
                "rating" : "4",
                "hours" : "9:00am - 11:00pm",
                "time_waiting" : "10",
                "image" : "1.jpg",
                "categories" : {
                    "data" : [
                        {
                            "id" : 1,
                            "name" : Seafood
                        },
                        {
                            "id" : 2,
                            "name" : Beef
                        }
                    ]
                },
                "description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum natus voluptates, velit quisquam, temporibus doloremque. Odio qui quis, magni, recusandae obcaecati debitis nobis ipsum aperiam. Tempora, quam molestias est vero?",
                "latitude": "10.710105",
                "longitude": "106.715846",
                "address" : "300 An Dương Vương Phường 10, Quận 5",
                "price" : "150.000 - 600.000",
                "payments" : {
                    "data" : [
                        {
                            "id" : 1,
                            "name" : "Cash"
                        },
                        {
                            "id" : 2,
                            "name" : "Paypal Payment"
                        },
                        {
                            "id" : 3,
                            "name" : "Online Payment"
                        }
                    ]
                },
                "parking" : {
                    "data" : [
                        {
                            "id" : 1,
                            "name" : "Street Parking"
                        },
                        {
                            "id" : 2,
                            "name" : "Parking Garage"
                        },
                        {
                            "id" : 3,
                            "name" : "Next Door"
                        }
                    ]
                },
                "menu_categories" : {
                    "data" : [
                        {
                            "id" : 1,
                            "name" : "Pizza",
                            "image" : "pizza.jpg"
                        },
                        {
                            "id" : 2,
                            "name" : "Burger",
                            "image" : "burger.jpg"
                        }
                    ]
                },
            }
        }

+ Response 404 (application/json)

        {
          "error" : {
            "http_code" : 404,
            "message" : "place Not Found"
          }
        }

## places Detail Reviews [/places/{id}/reviews]
+ Parameters

    + id (required, integer) ... The unique identifier of a place

### Get places Reviews [GET]

+ Response 200 (application/json)

        {
            "data" : [
                {
                    "user" : {
                        "data" : {
                            "id" : 1,
                            "fullname" : "Sarah Johnson",
                            "avatar" : "sarah-johnson.jpg"
                        }
                    },
                    "created_time" : "15:20",
                    "created_date" : "15.06.2016",
                    "content" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus ex beatae eos, facilis harum recusandae officiis tempora eum aut doloribus inventore nemo facere eaque quaerat cumque voluptatum tempore, eius qui.",
                    "images" : {
                        "data" : [
                            {
                                "id" : 1,
                                "image" : "1.jpg"
                            },
                            {
                                "id" : 2,
                                "image" : "2.jpg"
                            }
                        ]
                    }
                }
            ]
        }

+ Response 404 (application/json)

        {
          "error" : {
            "http_code" : 404,
            "message" : "place Not Found"
          }
        }

## Create Reviews [/reviews]

### Create place reviews [POST]

+ Request (multipart/form-data)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd


    + Body

            --__X_PAW_BOUNDARY__
				Content-Disposition: form-data; name="review"
				Content-Type: application/json
				
				{"place_id":"1","rating":"4","message":"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sit, nam eius sint, placeat officia saepe repellat libero quaerat beatae neque nesciunt esse enim quam doloremque numquam sapiente. Nam, sit, architecto!"}
				--__X_PAW_BOUNDARY__
				Content-Disposition: form-data; name="review_images[]"
				Content-Type: application/octet-stream
				
				
				--__X_PAW_BOUNDARY__
				Content-Disposition: form-data; name="review_images[]"
				Content-Type: application/octet-stream
				
				
				--__X_PAW_BOUNDARY__--

+ Response 201 (application/json)

        {
            "data" : {
                "user" : {
                    "data" : {
                        "id" : 1,
                        "fullname" : "Sarah Johnson",
                        "avatar" : "sarah-johnson.jpg"
                    }
                },
                "created_time" : "15:20",
                "created_date" : "15.06.2016",
                "content" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minus ex beatae eos, facilis harum recusandae officiis tempora eum aut doloribus inventore nemo facere eaque quaerat cumque voluptatum tempore, eius qui.",
                "images" : {
                    "data" : [
                        {
                            "id" : 1,
                            "image" : "1.jpg"
                        },
                        {
                            "id" : 2,
                            "image" : "2.jpg"
                        }
                    ]
                }
            }
        }

## places Detail Menu [/places/{id}/menu{?sortBy,categoryId}]
+ Parameters
    + id (required, integer) ... The unique identifier of a place
    + categoryId (required, integer, `1`)
    + sortBy (required, string, `delight`)
        + `delight`
        + `speed`
        + `price`

### Get places Menu [GET]


+ Response 200 (application/json)

        {
            "data" : [
                {
                    "id" : 1,
                    "name" : "Pizza",
                    "price" : "120.000 VND",
                    "description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit minus ad animi soluta voluptas doloremque expedita, esse, laborum aliquid officia facere! Labore et odit cupiditate minima, distinctio nam fugit eum.",
                    "image" : "pizza.jpg",
                },
                {
                    "id" : 2,
                    "name" : "Burger",
                    "price" : "90.000 VND",
                    "image" : "burger.jpg",
                    "description" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Odit minus ad animi soluta voluptas doloremque expedita, esse, laborum aliquid officia facere! Labore et odit cupiditate minima, distinctio nam fugit eum.",
                }
            ]
        }

+ Response 404 (application/json)

        {
          "error" : {
            "http_code" : 404,
            "message" : "place Not Found"
          }
        }


# Group Checkins
Checkins and History.

## Check-in [/checkins]

### Create Check-in [POST]

+ Request (application/json)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd


    + Body

            {
                "place_id": 1,
                "people" : 2
            }

+ Response 201 (application/json)

        {
            "data": [
                "id": 1,
                "place_id": 1,
                "time": 10,
                "created_at": "2017-04-02 18:30:00",
                "status" : "waiting"
            ]
        }

## Cancel Checkin [/checkins/cancel]

### Cancel Check-in [POST]

+ Request (application/json)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

    + Body

            {
                "checkin_id": 1
            }

+ Response 201 (application/json)

        {
            "data": [
                "id": 1,
                "place_id": 1,
                "time": 10,
                "created_at": "2017-04-02 18:30:00",
                "status" : "cancel"
            ]
        }

## Checkout [/checkouts]

### Checkout [POST]

+ Request (application/json)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

    + Body

            {
                "checkin_id": 1
            }

+ Response 201 (application/json)

        {
            "data": [
                "id": 1,
                "place_id": 1,
                "time": 10,
                "created_at": "2017-04-02 18:30:00",
                "status" : "complete"
            ]
        }

## Reservation [/reservations]

### Create Reservation [POST]

+ Request (application/json)

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

    + Body

            {
                "place_id": 1,
                "people" : 2,
                "date" : "Jan 2, 2016",
                "hours" : "7:00 AM",
                "note" : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptates itaque excepturi sit, corrupti quasi quam temporibus eaque perferendis accusamus quisquam adipisci soluta culpa et alias labore, facere in qui nobis."
            }

+ Response 201 (application/json)

        {
            "data": [
                "id": 1,
                "date": "7:00 PM Jan 2, 2017",
                "people": 2,
                "status" : "success",
                "code" : "T83F3"
            ]
        }

## Histories [/histories?page=2]

### Get Histories [GET]

+ Request

    + Headers

            X-Auth-Token : 4377316aa82e18a0d2358d759be1ee6f9c3368fd

+ Response 200 (application/json)

        {
            "data": [
                {
                    "id": 1,
                    "date": "06:07 AM Jan 13, 2017",
                    "code": null,
                    "people": 2,
                    "status": "waiting",
                    "type": "checkin",
                    "place": {
                        "data": {
                            "id": 1,
                            "name": "Karli",
                            "address": "78182 Kuhlman Hill\nLake Luigiton, MD 38272"
                        }
                    }
                },
                {
                "id": 3,
                "date": "16:39 PM Jan 18, 2017",
                "code": "FBE4A7",
                "people": 2,
                "status": "waiting",
                "type": "reservation",
                "place": {
                    "data": {
                        "id": 1,
                        "name": "Karli",
                        "address": "78182 Kuhlman Hill\nLake Luigiton, MD 38272"
                        }
                    }
                }
            ]
        }

# Group Promotions
Promotions.

## List Promotion [/promotions]

### GET List Promotion [POST]

+ Request (application/json)

    + Body

            {
                "page": 2,
                "number": 10
            }
        
+ Response 200 (application/json)

        {
            "data": [
                {
                    "id": 4,
                    "title": "Accusantium rem deleniti quia adipisci aut rem.",
                    "description": "Libero odit alias et enim. Reprehenderit autem voluptatem officiis laudantium.",
                    "image": "http://lorempixel.com/750/230/food/?38033",
                    "rating": 0,
                }
            ],
            "meta": {
                "pagination": {
                    "total": 1,
                    "count": 1,
                    "per_page": 10,
                    "current_page": 1,
                    "total_pages": 1,
                    "links": []
                }
            },        
        }

## Show Promotion [/promotions/{id}/show]

+ Parameters
    + id (required, integer)

### GET Show Promotion [GET]

+ Response 200 (application/json)

        {
            "data": {
                "id": 4,
                "title": "Accusantium rem deleniti quia adipisci aut rem.",
                "description": "Libero odit alias et enim. Reprehenderit autem voluptatem officiis laudantium.",
                "image": "http://lorempixel.com/750/230/food/?38033",
                "rating": 0,
                "place": {
                    "data": {
                        "id": 19,
                        "name": "Rhoda",
                        "address": "83024 Khalid Knolls Apt. 939\nNorth Roselynchester, VA 24628"
                    }
                }
            },        
        }

## Web View Promotion [/promotions/{id}/web-view]

+ Parameters
    + id (required, integer)

### GET Web View Promotion [GET]

+ Response 200 (text/html)


