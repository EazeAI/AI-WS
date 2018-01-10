
# AI-WS
#### Artificial Intelligence - Web Services
****

AI-WS is a set of ready to use RESTful webservices implementing various AI scenarios and models which user can call with necessary payload (data) and get the output back

### List of Services
- Natural Language Processing
  - Text Analysis
  - Sentiment Analysis
- Computer Vision
  - Image Processing

## Installation

Requirements:

* Python 2.7+ or 3.3+
* Flask 0.10+

Now run the webapp:

    $ python ./launch.py
     * Running on http://127.0.0.1:5000/
     * Restarting with reloader

You can now open a new tab and interact with the API from the command line:

    $ curl -X GET http://127.0.0.1:5000/

You can also work on the API directly in your browser, by opening <http://127.0.0.1:5000/>.  You can then navigate between notes, and make `GET`, `PUT`, `POST` and `DELETE` API requests.
