---
name: Cookie Data Analysis and Lead Prediction
tools: [Python, Tableau, AWS, Docker, FastAPI]
image: https://i.imgur.com/oHKiHKR.png
description: This project has an individual showcase page, not just a direct link to the project site or repo. Now you have more space to describe your awesome project!
---

# Cookie Data Analysis and Lead Prediction

Target marketing is the process of identifying the potential leads and focusing on promotion of products and services to those leads, thus increasing the lead conversion and customer acquisition.Here the data collected through cookies from a car manufacturer’s various online platforms such as its main website, and mobile applications is analyzed. The aim is to enable the car manufacturer to formulate its marketing mix based on the data scientific approach enriched by business insights. Adhering to the CRISP-DM methodology, the data is used to train machine learning models to predict whether the customer is a potential lead as well as the car models he is interested in. 

Also the geographical distribution of target customer segments is identified with unsupervised machine learning models.With the K-means clustering algorithm, the entire German market was divided into three segments - high, medium, and low preference groups for the target vehicle types. The cluster analysis output was later visualized using Tableau.The machine learning models are deployed as FastAPI in Heroku Cloud for production. 

<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://documentcloud.adobe.com/view-sdk-demo/PDFs/Bodea Brochure.pdf"}},
			metaData:{fileName: "Bodea Brochure.pdf"}
		}, {embedMode: "IN_LINE", showDownloadPDF: false, showPrintPDF: false});
	});
</script>

