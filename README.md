# BlogNews

![Linguagem mais usada](https://img.shields.io/github/languages/top/MatheusSC017/BlogNews)
![Numero de lingaugens usadas](https://img.shields.io/github/languages/count/MatheusSC017/BlogNews)
![Lincense](https://img.shields.io/github/license/MatheusSC017/BlogNews)
![Tamanho do projeto](https://img.shields.io/github/languages/code-size/MatheusSC017/BlogNews)

This project is a copy of another project of mine with some modifications to be deployed on Heroku, such as the addition of the Procfile and the configuration of the AWS S3 service. Follow the link to access the original [BlogNews project](https://github.com/MatheusSC017/BlogNews)

Access the website through this [link](https://blognews-a92f5c73f7ee.herokuapp.com/) (Link temporarily disabled)

## Requirements

Before running this code on heroku you need to set some environment variables

~~~
SECRET_KEY=secret_key_for_use_in_docker_change_me
DEBUG=1
DJANGO_ALLOWED_HOSTS=localhost 127.0.0.1 [::1]
DJANGO_CSRF_TRUSTED_ORIGINS=http://localhost:1337 http://127.0.0.1:1337

EMAIL_BACKEND=django.core.mail.backends.dummy.EmailBackend
EMAIL_HOST=''
EMAIL_HOST_USER=''
EMAIL_HOST_PASSWORD=''
EMAIL_PORT=587
EMAIL_USE_TLS=True
DEFAULT_FROM_EMAIL='BlogNews'

RECAPTCHA_SITE_KEY=6LeIxAcTAAAAAJcZVRqyHh71UMIEGNQ_MXjiZKhI
RECAPTCHA_SECRET_KEY=6LeIxAcTAAAAAGG-vFI1TnRWxMZNFuojJ4WifJWe
RECAPTCHA_SITE_KEY_TEST=6LeIxAcTAAAAAJcZVRqyHh71UMIEGNQ_MXjiZKhI
RECAPTCHA_SECRET_KEY_TEST=6LeIxAcTAAAAAGG-vFI1TnRWxMZNFuojJ4WifJWe

SQL_ENGINE=django.db.backends.mysql
SQL_DATABASE=blog_database
SQL_USER=blog_database_user
SQL_PASSWORD=blog_database_password
SQL_HOST=db
SQL_PORT=3306

DATABASE=mysql
INITIAL_DATA=True

SOCIALACCOUNT='{
	"google": {
		"APP": {
			"client_id": "",
			"secret": "",
			"key": ""
		}
	}
}'

AWS_ACCESS_KEY_ID=''
AWS_SECRET_ACCESS_KEY=''
AWS_STORAGE_BUCKET_NAME=''
AWS_S3_SIGNATURE_NAME=''
AWS_S3_REGION_NAME=''
~~~
