# Project Title

Vector  Space  Retrieval  using  Kibana  and  Elastic  Search

## Description
This  lab  involves  finding  Relevance  Score  corresponding  to  DocID  and  title.Also  to  find  valid  document  ID corresponding  to  the  asked  query.



### Executing program
To calculate the relevance score using Kibana and ElasticSearch  first  we  have  to  setup  both  of  them  in  localhost.
For kibana  the kibana.bat present  in  bin  folder  is  run  using terminal  and  similarly  for  Elastic  Search elasticsearch.yml in   bin folder  will  be executed.
After elastic  search(localhost:9200)executed  in  localhost successfully  then  run kibana (localhost:5601).
Now  to  make  sure  the  kibana  is working  properly  in  sync  with  elastic  search(kibana  devtools)  put  some  data(Eg:API  Requests)  and  run.After  then download the cran-exp.ndjson file and import on Kibana after giving index pattern.Finally then import the cran-exp.ipynb into Jupyter Note-book  or  VS  Code  and  analize  the  Relevance  Score  we  get corresponding to Document ID and Title



