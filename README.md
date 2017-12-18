# WebBlog

- This is a practise project from [Django: 1 Building a Blog](https://www.lynda.com/Django-tutorials/Django-1-Building-Blog/594453-2.html)
- Can use Markdown to write blog
- Using Solr + haystack as search engine
- Solving an haystack error caused by Django 1.11.x version[http://tumaolin.com/blog/2017/10/26/haystack/](http://tumaolin.com/blog/2017/10/26/haystack/)
- In the future, this blog will be deployed on AWS after adding new UI and modifying new features.
- [Demo](http://ec2-13-56-192-121.us-west-1.compute.amazonaws.com:8000/blog/)

## Notice
Everytime update posts, need to excute `python manage.py rebuild_index` to update search index

- Introduction of Solr
[https://lucene.apache.org/solr/guide/6_6/running-solr.html#running-solr](https://lucene.apache.org/solr/guide/6_6/running-solr.html#running-solr)
