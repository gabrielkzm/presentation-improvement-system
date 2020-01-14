# Presentation Improvement System
Presentation Improvement System is a web based project that helps students improve their presentation skills through the usage of artificial intelligence and natural language processing.

Students would first submit their audio recording to the application, the recording would then be processed through a speech to text tool. After initial transcribing and analysis generation, the application would provide the students with information and advice pertaining to filler word usage, pace, grammar error correction, as well as text summarisation, via a dashboard. Separately, students would be able to view their progress across multiple submissions, thus, identifying parts of their presentation that have been performing well, as well as work on aspects that needs improvements.

Through this analysis, students would be provided with useful feedback on their presentations, for self evaluation and improvement.

Professors would also have access to this application. They would be able to view students' submissions, identify weaker students, and provide feedback to the students, where neccessary. Separately, they would be able to classify and view statistics on both and individual and class level, thus, allowing them to plan their lessons well.

An admin portal has also been built to enable customization of third party speech to text APIs, filler word corpus customisation, bootstrapping of the system, as well as other customisation features required.

Technologies used:
- React
- Flask + Gunicorn
- PostgresSQL
- NGINX
- Docker
- TracisCI
- AWS (S3, Cloudfront, Elastic Load Balancer, EC2)
- Google Speech to Text
- Microsoft Azure Speech to Text
- Amazon Transcribe
- Several others

This repository serves as a facade for the actual source code. Actual source code and platform are hosted separate from this repository.

Should you wish to find out more, please reach out to me at my email (gabrielkoh@live.com) or via [linkedin](https://www.linkedin.com/in/gabrielkohzm).

