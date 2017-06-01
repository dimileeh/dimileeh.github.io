---
layout: post
title:  "Google Cloud Next London"
categories: google
tags: machine learning, cloud, serverless, deep learning
comments: true
---
On 3-4 May 2017, Google hosted its largest event in the UK - [Google Cloud Next London](https://g.co/nextlondon). The event took place at ExCel and gathered around 4,500 developers, IT professionals, entrepreneurs, executives and analysts. An introductory video invited participants to imagine the future that we all can create by harnessing the power of the Cloud and intelligent business models fuelled by the plethora of data that companies have been generating. Diane Greene - Senior Vice President - promptly reassured everyone that the data stored in the Cloud remains the property of the companies and that Google doesn't use it for its purposes.

Probably as a way to demonstrate the Cloud is not only a way to save on infrastructure costs and get started quickly for 21st-centuric start-ups but also a means to survive and compete for established companies with long history, HSBC - a global bank - were invited as the first guest speaker. HSBC Chief Architect Dr David Knott shared the bank's route from good old-fashioned relational databases, traditional data warehousing, then onto an ecosystem built with Hadoop and Spark. The latter proved that the abundance of data in itself is difficult to manage, and this is where Google Cloud with its machine learning models can make the difference.

Following that, Google showed a demo of their [Data Loss Prevention API](https://cloud.google.com/dlp/), which is still in beta. Personally identifiable information is a concern not only for the banks but also for all internet industry in highly-regulated Europe. The service detects sensitive information like credit card numbers, names, passport details and masks it automatically. Moreover, it was demonstrated to be intelligent enough to distinguish a valid credit card number from a fake one by verifying the checksum. "In the era when credit card details are sold on the black market with a 100% money-back guarantee" such service will become handy for companies that care about their reputation.

Tech companies are not the only ones that can benefit from the Cloud. Lush - a cosmetic manufacturer presented by shops around the globe - brought a delightful scent spread by a selection of their hand-made perfume to the floor with Google Partner stands. At the stage, Ryan Kerry, Global Head of Engineering and Technology at Lush, talked about how easily and quickly they managed to move their full IT infrastructure to the Cloud in just 22 days. Personally, I find it exciting when companies such as Lush that are in not in technology or Internet industries harness the latest technological advances to make improvements to their manufacturing, marketing and customer relationships. Google Cloud is just an instrument. It is what people do with it that makes the ultimate difference to how the world moves around.

The two-day agenda was packed with concurrently running 45-minute sessions covering the latest available Cloud technologies and announcing the ones to be released in the nearest future. To me, the topics covering machine learning and artificial intelligence were of interest but I also attended a few sessions on containers and serverless computing.

Ocado - an online supermarket - shared their experience of using machine learning for analysing emotional characteristics of customer emails, which at the expense of about $100/month brought a 10K% ROI in customer satisfaction and reduced costs on customer support. By doing such sentiment analysis, the algorithm prioritised emails that required a reply and archived the ones that did not. Remarkably, Ocado mentioned that they have their own tech team - [Ocado Technology](http://ocadotechnology.com/) - that writes all the retail software for the company and also actively recruits data scientists for building machine learning and artificial intelligence models.

At the event, I learned about some Cloud products that sparked my interest.

* [Google Cloud Container Engine (Kubernetes)](https://cloud.google.com/container-engine/) - container-centric infrastructure for developing and deploying applications, a standardised platform for reliable and scalable clusters without the operational overhead. Minicube - a local Kubernetes, easy to get started.

* [Firebase Database](https://firebase.google.com/) for real-time data synchronisation.

* [Google Cloud Machine Learning Engine](https://cloud.google.com/ml-engine/) represents a serverless TensorFlow. I have already tried it in action on [YouTube-8M Video Understanding Kaggle challenge](https://www.kaggle.com/c/youtube8m). All you need to do is to provide a configuration file for an environment and a Python script with a TensoFlow model in it. Upon firing a job, Google Cloud ML Engine will provision a virtual machine with the defined configuration, feed the logs either to the console or a web page, and save the learned model and any output (predictions for example) to the Cloud Storage.

* [Cloud Spanner](https://cloud.google.com/spanner/) - horizontally scalable relational database. With this great product, Google is aiming to revive interest in SQL databases by combining the convenience of predefined schema structure of traditional SQL and the scalability and flexibility of NoSQL databases.

* [Cloud Dataprep](https://cloud.google.com/dataprep/) - a tool for visual data exploration, clean up and preparation. It is still in private beta.

Overall, Google Cloud Next made a positive impression on me. From such little things as nice food at the venue and "Hosting you is kind of our thing" on the wall to the scale of the problems that Google is working on. I think Google is moving in the right direction and has the right idea that consists of providing the businesses with cutting edge technologies to help them solve the world problems.

All sessions can now be watched on the [Google website](https://cloudonair.withgoogle.com/events/next-live-emea-2017).

{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
**/

var disqus_config = function () {
this.page.url = "{{ page.url }}"";  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = "{{ page.id }}""; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};

(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://dmitri-lihhatsov-blog.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

{% endif %}
