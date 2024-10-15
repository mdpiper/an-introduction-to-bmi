# an-introduction-to-bmi

A presentation on the [Basic Model Interface](https://bmi.readthedocs.io) (BMI).

## presentation

Present these slides with [reveal-md](https://github.com/webpro/reveal-md) through their public Docker image:
```
git clone https://github.com/mdpiper/an-introduction-to-bmi
docker run --rm -p 1948:1948 -p 35729:35729 -v $PWD/an-introduction-to-bmi:/slides webpronl/reveal-md:latest /slides --watch
```
The service is now running at http://localhost:1948.
