# AWS Elastic Beanstalk example from [AWS Gentleman](https://awsgentleman.com/category/aws-cdk/) Twitch stream

## What is it?

It is an example that I have prepared for the [Twitch](https://twitch.tv/afronski) stream session from *AWS Certification* support group for *Associate level* preparations done as a part of [AWS Gentleman](https://awsgentleman.com) initiative.

## Prerequisites

- *MySQL >= 8.0*.
    - Use *Docker*: `docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=localInstance2020 -p 3306:3306 -d mysql:8`

## Examples

```bash
# Login:
curl -i -XPOST -H "Content-Type: application/x-www-form-urlencoded" -d "username=admin@example.com&password=12345" \
     http://localhost/login

# List all notes:
curl -i -H "Cookie: JSESSIONID=...; Path=/; HttpOnly" http://localhost/notes

# Create a note:
curl -i -XPUT -H "Cookie: JSESSIONID=...; Path=/; HttpOnly" -H "Content-Type: application/json" \
     -d '{"title": "1st note", "message": "message", "location": "Poland"}' http://localhost/notes
```

## Deployment

- 

## License

- [MIT](LICENSE.md)

## Authors

- [Wojciech Gawroński (afronski) - AWS Gentleman](https://github.com/afronski)
