# Kibana

### Getting Started
* launch the service
 * `./bin/kibana`

### Access
* 127.0.0.1:5601

### query
* equal(`...==...`), inequal(`!...==...`)
* greater (`...:>...`)

### Data Visualization
##### Getting Started
    * metrics: similar to the **value** of y-axis
    * bucket: similar to the **set** of data of x-axis
##### Aggragation (Supported by Elasticsearch)
    * unique count
    * count
    * max... etc

#### Problem
* Cannot use .raw filed in Kibana.
 * [Confused about how to use .raw fields and not analyze string fields](https://discuss.elastic.co/t/confused-about-how-to-use-raw-fields-and-not-analyze-string-fields/28106)