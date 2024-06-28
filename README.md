# Dream-Machine-API
PiAPI's unofficial [Dream Machine API](https://piapi.ai/dream-machine-api), launched by Luma Labs, equips developers with state-of-the-art video generation tools for an enhanced user experience.

<img src="https://github.com/PiAPI-1/Dream-Machine-API/assets/173328932/ee762dcb-7e5d-4ca0-814a-3db9f68507a5" alt="screenshot of the Midjourney API page from PiAPI" width="95%"/>

<br><br>

<h2>Features</h2>
<ol>
  <li>Image Upload Supported</li>
  <li>Enhance Prompt Feature Supported</li>
  <li>Bulk Generation Available</li>
  <li>Pay-as-you-go and Host-your-account Options</li>
  <li>Asynchronous API Calls</li>
  <li>Watermark Removal</li>
  <li>Priority Generations</li>
  <li>Commerical Use</li>
  <li>Extend Function Coming Soon</li>
</ol>

<br><br>

<h2>Usage Options</h2>

<h3>Pay-as-you-go Option</h3>

<p>
  To get started, simply sign up and purchase credits in our <a href="https://app.piapi.ai/">Workspace</a>. Once done, you can immediately access our API! Our service leverages PiAPI’s Dream Machine account pools, ensuring seamless operation without any hassle on your part.
</p>

<ul>
  <li>No need for your own Dream Machine account(s) pool</li>
  <li>No need to manage or operate Dream Machine accounts</li>
  <li>Full access to all endpoints</li>
  <li>Start integrating the API immediately!</li>
</ul>

<br>

<h3>Host-your-account Option</h3>

<p>
  When you choose our Host-Your-Account service, you'll use your own Dream Machine Account(s). Then you can subscribe to PiAPI's Dream Machine API seat(s), connecting your Dream Machine account(s) to the seat(s), and you're ready for integration!
</p>

<ul>
  <li>Faster generation time</li>
  <li>Supports hosting of multiple accounts</li>
  <li>Stable API service</li>
</ul>

<br>

<h3>Pricing</h3>

<h4>Pay-as-you-go Option</h4>

<ul>
  <li>Standard: $0.30/call</li>
  <li>Custom Dedicated Deployment: Contact us via email!</li>
</ul>

<h4>Host-your-account Option</h4>

<ul>
  <li>Flat pricing: $<b>10</b>/seat/month</li>
</ul>

<br>

Please refer to our <a href="https://piapi.ai/pricing">pricing page</a> for more information.

<br><br>

<h2>Usage Steps</h2>
<h3>Pay-as-you-go Option</h3>
<ul>
  <li>Register for PiAPI's Workspace using your GitHub account.</li>
  <li>Obtain your API KEY from our <a href="https://app.piapi.ai/">Workspace</a></li>
  <li>Start coding right away!</li>
</ul>
<br>
<h4>Sample API Calls (using cURL)</h4>
<br>
<p>Create a Video Generation call</p>

```
curl --request POST \
  --url https://api.piapi.ai/api/luma/v1/video \
  --header 'Accept: application/json' \
  --header 'Content-Type: application/json' \
  --header 'X-API-Key: ' \
  --data '{
  "prompt": "flying cat",
  "expand_prompt": true
}'
```
<p>Response</p>

```
{
  "code": 200,
  "data": {
    "task_id": "record_this_taskID"
  },
  "message": "success"
}
```
<br>
<p>Get the Video Generation call</p>

```
url --request GET \
  --url https://api.piapi.ai/api/luma/v1/video/task_id \   //Replace the task_id with the returned task_id
  --header 'Accept: application/json'
```
<br>
<p>Response - Check out our <a href="https://piapi.ai/docs/dream-machine/get-video">documentation</a> for more information!</p>
<br>
<br>

<h2>Contact us</h2>

<p>Email: <a href="mailto:contact@piapi.ai">contact@piapi.ai</a></p>

<br>
