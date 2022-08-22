# Microservice Course

### Endpoints

### Save Course

POST /api/course/ HTTP/1.1
Host: localhost:3333
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Content-Type: application/json
Cookie: JSESSIONID=373D1B050516FCAF2B8B3991DB72155E
Content-Length: 91

{
"title": "test-course-2",
"subtitle": "test-course-subtitle-2",
"price": 25
}

### Get Courses

GET /api/course/ HTTP/1.1
Host: localhost:3333
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Content-Type: application/json
Cookie: JSESSIONID=373D1B050516FCAF2B8B3991DB72155E
Content-Length: 91

{
"title": "test-course-2",
"subtitle": "test-course-subtitle-2",
"price": 25
}

### Delete Courses
DELETE /api/course/ HTTP/1.1
Host: localhost:3333
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Content-Type: application/json
Cookie: JSESSIONID=373D1B050516FCAF2B8B3991DB72155E
Content-Length: 91

{
"title": "test-course-2",
"subtitle": "test-course-subtitle-2",
"price": 25
}


