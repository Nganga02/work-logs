# ALX Month 01 log

+ Worked on database connection and improved queries using sql db technologies like postgresql, sql and sqlite

Key takeaways
-------------
1. Learnt sql langugage and advanced sql functionalities 
1. Got an intro into python's backend framework(Django)
1. Made some small projects using the technologies learnt to gain insight on how the backend works
[alx python back-end](https://github.com/Nganga02/alx-backend-python),
[alx airbnb database](https://github.com/Nganga02/alx-airbnb-database)


# week 01
## 09 Nov - 16 Nov
Had the opportunity to work on unit testing and integration testing: 
Understood the python's unittest module

**Repo**: [alx-python-backend/0x03](https://github.com/Nganga02/alx-backend-python/tree/master/0x03-Unittests_and_integration_tests)

Delved into the django rest framework introduction and had an interesting time understanding views, models, urls, serializers. I came across this interesting diagram from claude which helped me stitch it all together.


*For this you have to view it in the raw for to get the better view*

┌──────────────┐
│   Client     │  (Browser, Mobile App, etc.)
│  (HTTP)      │
└──────┬───────┘
       │ JSON Request
       ▼
┌──────────────────────────────────────────┐
│           URLS (urls.py)                 │  Routes requests
└──────┬───────────────────────────────────┘
       │
       ▼
┌──────────────────────────────────────────┐
│          VIEWS (views.py)                │  Business logic & orchestration
│  - Receives HTTP request                 │
│  - Validates permissions                 │
│  - Calls Model to get/save data          │  ← Interacts with database
│  - Passes data to Serializer             │
│  - Returns HTTP response                 │
└──────┬───────────────────────────────────┘
       │                    ▲
       │                    │
       ▼                    │
┌──────────────────┐  ┌─────────────────┐
│   SERIALIZERS    │  │     MODELS      │  ← ONLY component that talks to DB
│  (serializers.py)│  │   (models.py)   │
│                  │  │                 │
│  - Validates data│  │  - ORM layer    │
│  - Converts:     │  │  - SQL queries  │
│    Python ↔ JSON │  │  - CRUD ops     │
│                  │  │                 │
└──────────────────┘  └────────┬────────┘
                               │
                               ▼
                      ┌─────────────────┐
                      │    DATABASE     │
                      │   (PostgreSQL,  │
                      │   SQLite, etc.) │
                      └─────────────────┘ 


# Week 02
## 17-24 Nov
For this week major concentration was on the following for the __backend__

| Tool/Library |	Purpose                                              |
|--------------|----------------------------------------------------------|
Django Allauth | 	Streamlined user authentication, including email verification and social auth
Django REST Framework (DRF) |	Token and session authentication for APIs
SimpleJWT / djangorestframework-simplejwt |	Lightweight JWT authentication for DRF
OAuthLib / django-oauth-toolkit |	Secure OAuth2 implementation in Django
Guardian |	Object-level permissions and per-instance access control
Auth0 |	Third-party identity and access management integration
Keycloak |	Open-source identity provider for managing enterprise SSO
Okta |	       Enterprise IAM provider with SSO, MFA, and directory services
PyJWT |	Lightweight JWT token generation and validation
Auditlog |	Automatic tracking of model changes and user actions for audit trails

And the following for __engineering programming__\
1. Initialize a project on truss
2. Finish the course on linear algebra

The following were the findings for this week: