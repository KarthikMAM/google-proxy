# Setting up a proxy server on Google Appengine

<h4>Steps</h4>
<ol>
  <li>Go to <a href="appengine.google.com">Appengine</a> and create a new project
  <li>Pick an <b>appid</b> and note it down
  <li>Download the <a href="https://storage.googleapis.com/appengine-sdks/featured/GoogleAppEngine-1.9.26.msi">appengine SDK</a>
  <li>Install the appengine SDK
  <li>Download the <a href="https://github.com/KarthikMAM/google-proxy/archive/master.zip">Project files</a> and extract it.
  <li>Open the appengine SDK and go to <b>File->Add Existing application</b> and select the extracted folder.
  <li>Open the <b>app.yaml</b> file and replace the appid with your appid.
  <li>Now, click <b>deploy</b> and enter your Google login if it prompts.
  <li>Now, your proxy server is deployed to <b>appid.appspot.com</b>
</ol>
