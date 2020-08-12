<Docker's Purpose> Ease the workflow It's not a requirement but it makes the
workflow way easier

In Development In Production Docker Container Docker Container npm run start npm
run build

- development mode에서 Dockerfile.dev를 만들어서 사용 할 경우

- docker build -f(file) Dockerfile.dev .

- docker volumes

-set up a placeholder of sources inside of our container it's not a copy of
images instead, it refers to local machine
