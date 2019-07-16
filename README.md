# Awesome Qlik Analytics Platform (QAP)

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![CircleCI](https://img.shields.io/circleci/project/github/stefanwalther/awesome-qap.svg)](https://circleci.com/gh/stefanwalther/awesome-qap)

A collection of awesome resources related to several Qlik Sense integration topics resp. Qlik Analytics Platform (QAP) topics. Inspired by [awesome lists](https://github.com/sindresorhus/awesome).

<h1 align="center">
	<img width="800" src="https://raw.githubusercontent.com/stefanwalther/awesome-qap/master/media/awesome-qap.png" alt="Awesome Qlik Analytics Platform (QAP)">
	<br>
	<br>
</h1>

<p align="center">
	<a href="CONTRIBUTING.md">Contribution guide</a>, just use your browser ... so easy ...
</p>

<br/>

# Table of Contents

- [Contents](#contents)
	- [Integration Overview](#integration-overview)
	- [Solutions built on top of QAP](#solutions)
		- [On Demand App Generation](#on-demand-app-generation)
	- [APIs](#apis)
		- [Capability APIs](#capability-apis)
		- [Engine API](#engine-api)
		- [Mashup API](#mashup-api)
		- [Visualization API](#visualization-api)
		- [.NET SDK](#net-sdk)
	- [Connectivity](#connectivity)
	- [DevOps](#devops)
	- [Extending Qlik Sense](#extending-qlik-sense)
		- [Widget Libraries](#widget-libraries)
		- [Building Visualization Extensions](#building-visualization-extensions)
		- [Visualization Extensions](#visualization-extensions)
	- [Manageability](#manageability)
		- [Qlik Sense Repository (QRS) API](#qlik-sense-repository-api)
		- [Qlik Sense QMC Utilities](#qlik-sense-qmc-utilities)
	- [Security](#security)
	- [Server Side Extensions / Advanced Analytics](#server-side-extensions-sse--advanced-analytics-aai)
	- [Web Development](#web-development)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

---

# Contents

## Integration Overview

- [Qlik Analytics Platform / QAP](http://help.qlik.com/en-US/sense-developer/2.2/Subsystems/Platform/Content/Architecture/qlik-analytic-platform.htm) - Overview of the Qlik Analytics Platform

## Solutions
Solutions built on top of Qlik Analytics Platform / leveraging APIs of QAP:

- [Fasttrack](https://github.com/jacobvinzent/Fasttrack) - Transfer dimensions and expressions from QlikView 11 to Qlik Sense.
- [QLIK-Visualization-API-json-file](https://github.com/jacobvinzent/QLIK-Visualization-API-json-file) -  Reuse your application design done in the Qlik Sense Desktop or on the Qlik Enterprise server across multiple applications for different customers.
- [SaaS Demo](https://github.com/QHose/QRSMeteor) - SaaS API automation demo.
- [mdemo](https://github.com/aalteirac/mdemo) - A Qlik Sense Mashups demo Extension for Qlik Sense Desktop and Qlik Sense Server.

### On Demand App generation

- [On demand app generation](https://github.com/websy85/on-demand-app-gen) - A simple On-demand app generation extension for Qlik Sense.
- [app-on-demand](https://github.com/bardess/app-on-demand) - On demand app generation.
- [architeqt](https://github.com/mindspank/architeqt) - Generated Qlik Sense apps from a template.
- [Qlik ODAG Elastic Search](https://github.com/pouc/qlik-odag-elastic-search) - Generated Qlik Sense apps from ElasticSearch.
- [QlikSocial](https://github.com/johsund/QlikSocial) - Social Media on demand app generator for Qlik Sense.
- [Qlik Data Concierge](https://github.com/QlikPreSalesDACH/Qlik-Data-Concierge) - A self-service solution for non-technical BEx users based on Qlik Sense.
- [app-on-demand](https://github.com/bardess/app-on-demand) - On demand app generation.
- [architeqt](https://github.com/mindspank/architeqt) - Generated Qlik Sense apps from a template.
- [Qlik ODAG Elastic Search](https://github.com/pouc/qlik-odag-elastic-search) - Generated Qlik Sense apps from ElasticSearch.
- [QlikSocial](https://github.com/johsund/QlikSocial) - Social Media on demand app generator for Qlik Sense.
- [Qlik Data Concierge](https://github.com/QlikPreSalesDACH/Qlik-Data-Concierge) - A self-service solution for non-technical BEx users based on Qlik Sense.
- [Introduction to On Demand Apps](https://extendingqlik.upper88.com/qlik-sense-on-demand-apps/) - Introduction to On Demand Apps by Erik Wetterberg.

## APIs

### Capability APIs

- [WebPack-CapabilityAPIs](https://github.com/mindspank/webpack-capabilitiesapi) - Examples how to use the Capability APIs in combination with WebPack.


### Engine API

- [Introduction to Generic Object](https://community.qlik.com/docs/DOC-7732) - Very detailed explanation of the Generic Object, which is the foundation for all visualizations in Qlik Sense.
- [qsocks](https://github.com/mindspank/qsocks) - A lightweight promise wrapper around the Qlik Sense Engine API.
- [Engine API Explorer](http://qliksite.io/qlik-sense/introducing-engine-api-explorer/) - Introduction to the Engine API Explorer (a part of Dev Hub).
- [Engine API and qSocks](https://community.qlik.com/blogs/qlikviewdesignblog/2015/07/20/engine-api-and-qsocks-connecting-and-getting-a-list-of-available-apps) - Engine API and qSocks - Connecting and getting a list of available apps.
- [QlikSenseAngularDemo](https://github.com/thomasfriebel/QlikSenseAngularDemo) - A lightweight browser demo of the new Qlik Engine API.
- [Qlik REST In Sense (otto)](https://github.com/ralfbecher/q-risotto) - A RESTful Engine API wrapper to easily accessapps, objects and its data on a Qlik Sense server thru a REST API to integrate with other systems.
- [QIX Struct Generator](http://opensrc.axisgroup.com/qix-struct-generator/) - QIX Engine Struct Generator.

### Mashup API

- [Mashup API Tutorials](https://community.qlik.com/thread/140982) - Great series of tutorials how to get started with Mashups.
- [Extensions to the Mashup API](https://github.com/websy85/extended-mashup-api)
- [Qlik Analytics for Visual Studio](https://marketplace.visualstudio.com/items?itemName=QlikDeveloperToolkit.QlikAnalyticsforVisualStudio) - Visual Studio plugin to integrate Qlik Sense visualizations into an existing web site.
- [Handle errors in your Qlik Sense mashup](https://extendingqlik.upper88.com/handle-errors-in-your-qlik-sense-mashup/) - Handling Errors within Mashups.

### Visualization API

- [The Visualization API - An Overview](https://community.qlik.com/docs/DOC-16768) - Great overview of the Visualization API, created by Erik Wetterberg.
- Some great gists, using the Visualization API:
    - [Basic Visualization API example.](https://jsfiddle.net/mindspank/803627ug/) - Connecting to Qlik Sense and displaying fully interactive graphs based on Qlik data.
    - [Patching properties on the fly](https://jsfiddle.net/mindspank/b6zob8ku/) -
    - [Selective Data points](https://jsfiddle.net/mindspank/1zqp7zuc/) -
    - [Visualization API and Extensions on the fly](https://jsfiddle.net/mindspank/rnmka3zh/) - Loading on the fly extensions and using the visualization api to display them.
- [Introduction to Generic Object](https://community.qlik.com/docs/DOC-7732) - Very detailed explanation of the Generic Object, which is the foundation for all visualizations in Qlik Sense.

### .NET SDK

- [.NET SDK Examples](https://github.com/AptkQlik/PublicExamples) - Some examples using the .NET SDK.
- [Reloader NTLM](https://github.com/AptkQlik/Reloader_NTLM) - Example how to avoid consuming license tokens and how to use other credentials than the logged on user.
- [SDKConnectionWithSenseTicket](https://github.com/AptkQlik/SDKConnectionWithSenseTicket) - Connect with the Qlik Sense .Net SDK using an existing session.
- [ScriptReloader](https://github.com/AptkQlik/ScriptReloader) - Illustrate how one can decompose a Qlik Sense App so that scripts can be reloaded from an external server.
- [QlikSenseScriptObfuscater](https://github.com/AptkQlik/QlikSenseScriptObfuscater) - A way to hide scripts with .Net SDK in Qlik Sense.

## Connectivity

- [Butler for Qlik Sense](https://github.com/mountaindude/butler) - Connectivity proxy for Sense, features such as posting to Slack from load script, real-time forwarding of reload failures and user login/logout events to Slack and MQTT, and others.
- [Butler MQTT](https://github.com/mountaindude/butler-mqtt) - Slimmed down version of Butler, only including the REST-to-MQTT bridge. useful for creating real-time script reload dashboards.
- [halyard.js](https://github.com/qlik-oss/halyard.js) - JavaScript library for generating Qlik Load Scripts using an abstracted API (Official Qlik OSS project).
- [Qlik Connector to Execute PS Scripts](https://github.com/konne/qlik-connector-psexecute) - A Qlik Connector to execute PowerShell scripts.

## DevOps

- [SenseOps](https://senseops.rocks) - Qlik Sense + DevOps = SenseOps. Thoughts on best practices for using Sense in the enterprise.
- [Butler SOS](https://github.com/mountaindude/butler-sos) - Grafana powered real-time operational dashboards for Qlik Sense enterprise.
- [Butler CW](https://github.com/mountaindude/butler-cw) - Flexible cache warming for Qlik Sense. Apps can be loaded on schedule or with desired frequency into QIX engine on specific servers, with an option to also pre-calculate all objects on all sheets. This can dramatically improve the perceived app load times and responsiveness seen by end users.
- [Qlik Sense app duplicator](https://github.com/mountaindude/sense-template-app-duplicate) - A Node.js microservice is combined with a web frontend and Sense apps tagged as templates in the QMC. The result is a tool that allows users to create new Sense apps within seconds, where the apps then also adhere to the coding standards implemented in the template apps. Saves time and improves app quality.

## Extending Qlik Sense

### Widget Libraries
Some collections of Widgets:

- [Irregular Widgets](https://github.com/ralfbecher/irregular-widgets) Widget Library created by Ralf Becher.
- [SenseUI-Widgets](https://github.com/yianni-ververis/SenseUI-WidgetLibrary) - The Widget library created by Qlik's demo team.
- [Themed Widgets](https://github.com/newmans99/Themed-Widgets) - Qlik Sense UI Widgets supporting themes.


## Building Visualization Extensions

- [Accessing system data and variables in a Qlik Sense extension](http://extendingqlik.upper88.com/accessing-system-data-and-variables-in-a-qlik-sense-extension/) - Erik Wetterberg elaborates on the most efficient way to get access to system data.
- [D3 & Visualization Extensions](https://community.qlik.com/docs/DOC-16346) - Tutorial on using D3 in Qlik Sense Visualization Extensions.
- [ES6, Babel, Webpack & GulpJS](https://github.com/alner/NewQlikSenseVisualizationTemplate) - Template for developing visualization extensions, using ES6, Babel, Webpack & GulpJS).
- [Exporting Qlik Sense extensions to Powerpoint and PDF](https://extendingqlik.upper88.com/exporting-qlik-sense-extensions-to-powerpoint-and-pdf/) - How to enable export to PowerPoint & PDF in visualization extensions.
- [Lasso filtering](http://www.axisgroup.com/lasso-filtering-in-qlik-sense-extensions/) - Lasso filtering in Qlik Sense Visualization Extensions.
- [Lasso plugin](https://github.com/skokenes/D3-Lasso-Plugin) - D3 plugin, very similar to the lasso in Qlik Sense.
- [Using Bootstrap CSS in Qlik Sense Visualization Extensions](http://qliksite.io/qlik-sense/using-bootstrap-css-qliksense-visualization-extensions/) - How to prevent clashes between Qlik Sense' CSS files and those from Bootstrap.
- [Using enigmajs in your Qlik Sense extension](https://extendingqlik.upper88.com/using-enigmajs-in-your-qlik-sense-extension/) - How to use enigma.js in your visualization extension.
- [qext CLI](https://medium.com/axis-group-visual-analytics-practice/qlik-sense-extension-development-with-qext-646c98dc9ae1) - qext, a CLI tool to create Visualization Extensions.
- [Qlik Sense Extension Tutorial](https://github.com/stefanwalther/qliksense-extension-tutorial) - Living tutorial on how to create visualization extensions, including sample code.
- [Qlik Sense Extension with D3](http://www.axisgroup.com/tutorial-how-to-build-a-qlik-sense-extension-with-d3/) - Tutorial: How to Build a Qlik Sense Extension with D3.
- [Qlik-Sense-D3-Visualization-Library](https://github.com/skokenes/Qlik-Sense-D3-Visualization-Library) - A library of d3 visualizations housed in 1 Qlik Sense extension.

## Visualization Extensions
A selection of the most popular or interesting visualization extensions, you'lll find much more on [branch.qlik.com]http://branch.qlik.com/#!/project).

- [AnyChart - charts and dashboards](https://github.com/AnyChart/AnyChart-Qlik) - AnyChart JavaScript Visualization Library extension for Qlik Sense and Qlik View..
- [Climber Cards](https://github.com/ClimberAB/ClimberCards) - Table extension with cards as cells.
- [Climber Custom Report](https://github.com/ClimberAB/ClimberCustomReport) - Create custom reports in Qlik Sense.
- [Climber KPI](https://github.com/ClimberAB/ClimberKPI) - Create nicely formatted KPI objects with background trends.
- [Climber Selection Bar](https://github.com/ClimberAB/ClimberSelectionBar) - Horizontal selection bar with pre-selected values.
- [D3 Visualization Library](https://github.com/skokenes/Qlik-Sense-D3-Visualization-Library) - A single extension that hosts 30 example charts from the d3 gallery..
- [deltaViz self service dashboard](https://github.com/yblake/deltaViz) - Dashboard extension.
- [Google Annotation Chart](https://github.com/yianni-ververis/google-annotation-chart)
- [PL Smart Pivot](https://github.com/iviasensio/PLSmartPivot) - Improved Reporting Extension.
- [Qlik Sense 2 Dimensional Heatmap](https://github.com/ralfbecher/QlikSense_Extension_2DimHeatmap) - D3 based colored tile matrix.
- [Qlik Sense D3 Scatter Plot Chart](https://github.com/paulosoaresf/qlik-sense-d3-scatter-plot-chart) - Scatter Plot Chart.
- [Qlik Sense interactve Timeline](https://github.com/ralfbecher/QlikSense_Extension_Timeline) - Timeline chart.
- [Qlik Sense Reload Button](https://github.com/mhamano/Qlik-Sense-Reload-Button) - Execute a load script from within an extension.
- [qse-mgoimagegrid](https://github.com/murraygm/qse-mgoimagegrid) - Display images in a grid.
- [qsVariable](https://github.com/erikwett/qsVariable) - Sense Variable extension.
- [SenseDateRangePicker](https://github.com/NOD507/SenseDateRangePicker) - Sense Date Range Picker.
- [SenseSankey](https://github.com/xavierlp/SenseSankey) - Sankey Chart.
- [Sheet Navigation + Actions for Qlik Sense](https://github.com/stefanwalther/sense-navigation) - Add buttons with action/macros to Qlik Sense.
- [Simple KPI](https://github.com/alner/qsSimpleKPI) - Create nicely formatted KPI objects.
- [SVG Map Extension](https://github.com/brianwmunz/svgReader-QV11) - Visualizing data on an image or map.
- [Tabbed Container Extension](https://github.com/dfarache/Tabbed-Container-Extension) - A Qlik Extension that groups Sense objects in a container and displays tabs as a way of navigating through them.
- [Waterfall extension](https://github.com/NielsLindberg/Qliksense.Extension.amWaterfall) - Waterfall extension based on amCharts.
- [Word Cloud for Sense](https://github.com/cleveranjos/br.com.clever.wordcloud) - Word Cloud extension.
- [xGridResizer](https://github.com/ludberg/xGridResizer) - This extension lets you resize the grid of a sheet in Qlik Sense. (Attention: absolutely not supported and very experimental).
- [xTableBox](https://github.com/ludberg/xTableBox) - Display all columns of a table, very usefull during the data-modelling process.

## Manageability

### Qlik Sense Repository API

- [Qlik-Cli](https://github.com/ahaydon/Qlik-Cli) - PowerShell Cmdlets to talk to the QRS API.
- [QlikSensePowerShell](https://github.com/JoeBickley/QlikSensePowerShell) - A powershell plugin with common Qlik Sense automation functions.
- [qrs](https://github.com/stefanwalther/qrs) - Node.js library to communicate with Qlik Sense Repository Service (QRS) API.
- [qrs-interact](https://github.com/eapowertools/qrs-interact) - QRS Interact is a simple javascript library that allows users to send queries to the Qlik Sense Repository Service.


### Qlik Sense QMC Utilities

A collection of management console utilities for use with Qlik Sense.

- [App Meta Fetcher](https://github.com/eapowertools/qmcu-app-meta-fetcher) - App Meta Fetcher is used in conjunction with the Governed Metrics Application (included in the Governed Metrics Service installation). This plugin outputs Site-level application metadata into a collection of csv files which can be used to identify application, master and non-master item, visualization, and sheet metadata.
- [App Mover](https://github.com/eapowertools/qmcu-app-mover) - App Mover is a tool to help administer application movement from site to site. It allows exporting from one Qlik Sense environment and importing into 1 or many Qlik Sense environments.
- [App Object Approver](https://github.com/eapowertools/qmcu-appobject-approver) - The App Object Approver enables approval of published sheets, stories, bookmarks, dimensions, measures, and Master Items in an app, thus, making them base objects of the Qlik Sense application. In addition, it's possible to un-approve objects as well and push them back to the community.
- [Custom Property Bulk Loader](https://github.com/eapowertools/qmcu-custom-prop-loader) - The Custom Property Bulk Loader enables administrators to upload a list of values for managing custom properties without having to enter values manually. The bulk loader is able to update existing custom properties, or create new custom properties for a Qlik Sense deployment. Select a custom property or provide a name, select the resources the custom property will apply to, and upload a csv file with a single column list of values. Once that's done click the Create or Update button and to add or modify the custom property.
- [Real QMC](https://github.com/eapowertools/qmcu-real-qmc) - The Actual Qlik Management Console in QMC Utilities.
- [Security Rule Manager](https://github.com/eapowertools/qmcu-rule-manager) - The Security Rule Manager allows a Qlik Sense administrator to export and import security rules from the Qlik Sense repository. This is helpful if you have developed a security model in one environment and would like to bring the whole model (or even specific security rules) over to a different environment.
- [Source Control Assistant](https://github.com/eapowertools/qmcu-sclite) - The Source Control Assistant is an application backup and restore solution for Qlik Sense.  Apps are serialized to json files, which can be easily stored and versioned in popular source control systems like Subversion, TFS, and Github.


## Security

- [Authenticating with certificates](http://qliksite.io/qlik-sense/authentication-certificates/) - A step-by-step guide how to set up, configure and use certificates for authentication.
- [AccessControlTestModule](https://github.com/flautrup/AccessControlTestModule) - Authentication module for Qlik Sense to be used to test Access Control.
- [Using Header Authentication](http://qliksite.io/qlik-sense/header-authentication-configuration/) - A step-by-step guide how to set up and use header authentication.
- [qlik-auth](https://github.com/braathen/qlik-auth) - Node.js library to simplify custom authentication with both QlikView and Qlik Sense.
- [qlik-auth-net](https://github.com/braathen/qlik-auth-net) - Asp.net module for simplifying custom authentication with Qlik Sense.
- [qlik-auth-google](https://github.com/braathen/qlik-auth-google) - Qlik Sense OAuth2 authentication module designed specifically for Google services.
- [qlikoauth](https://github.com/braathen/qlikoauth) - Demonstration using OAuth 2.0 for QlikView and Qlik Sense integration.
- [Chrome Security Rule Management](https://github.com/flautrup/ChromeRuleManagement) - Chrome app developed to help the reuse and transfer of rules between Qlik Sense environments.
- [Using Capability APIs with tickets](https://github.com/mindspank/express-qps-sample) - Example how to use [Express](http://expressjs.com/) to host a page using the Capabilities API from Qlik Sense.

## Server Side Extensions (SSE) / Advanced Analytics (AAI

### SSE/AAI Official Resources & Help

- [Server Side Extension](https://github.com/qlik-oss/server-side-extension) - A Qlik server-side extension protocol for extending the Qlik built-in expression library with functionality from external calculation engines.
- [Server Side Extension - R-plugin](https://github.com/qlik-oss/sse-r-plugin) - A Qlik server-side extension plugin for accessing R.
- [Creating an analytic connection / QMC](https://help.qlik.com/en-US/sense/June2017/Subsystems/ManagementConsole/Content/create-analytic-connection.htm)
- [Configuring an analytic connection / Desktop](https://help.qlik.com/en-US/sense/June2017/Subsystems/Hub/Content/Introduction/configure-analytic-connection-desktop.htm)

### SSE/AAI - Plugins
- [Qlik Sense Analytic Extension for Security](https://github.com/flautrup/SecSSE) - PoC to show how server side extensions can be used to extend the scripting of Qlik Sense with aditional security functions to protect customer information.
- [Python data science tools for Qlik](https://github.com/nabeel-oz/qlik-py-tools) - Provides a server side extension (SSE) for Qlik Sense built using Python. The intention is to provide a set of functions for data science that can be used as expressions in Qlik.

### SSE/AAI - Solutions
- [AAI Expression Builder](https://github.com/AnalyticsEarth/AAIExpressionBuilder) - The AAI Advanced Analytics Expression Builder is a Qlik Sense extension used to create advanced analytics expressions as master items and wrap these in to a prebuilt visualization.
- [Advanced Analytics Toolbox](https://github.com/mhamano/advanced-analytics-toolbox) - Qlik Sense extension which allows you to create charts to perform advanced analytics by simple drag and drop without complex scripting.

### SSE/AAI - Articles
- [Qlik Sense R-Plugin as Windows Service](https://community.qlik.com/blogs/qlikviewdesignblog/2017/07/07/automatically-start-the-r-plugin) - Run the Qlik Sense R-Plugin as a Windows service.
- [Server Side Extensions Tutorial](http://www.axisgroup.com/qlik-sense-server-side-extensions-part-13-architecture-environment/) - Three part tutorial to get started with Server Side Extensions, provided by AxisGroup.

## Web Development

- [Qlik React Starter](https://community.qlik.com/blogs/qlikviewdesignblog/2018/01/19/starter-project-for-developing-qap-powered-apps-with-react-and-enigmajs) - Starter template for creating projects powered by Qlik using enigma.js and React.

# Related Awesome Lists

- [awesome-picasso.js](https://github.com/stefanwalther/awesome-picasso.js) - A curated list of awesome resources for the awesome picasso.js library.


# Contributing

Contributions are not only always welcome but the entire idea behind this list!
**There is no need to install any tool, to understand git, just use your browser!**

Please take a look at the [contribution guidelines and quality standard](CONTRIBUTING.md) page first.

# License

[![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
