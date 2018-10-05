# DevOps Maturity Assessment

## Overview

This is a simple, survey-based tool, to help teams assess where they currently are on their DevOps journey and to help them identify next steps.

## Installation

This is a PHP application that should run on any server that supports PHP 5.6 or higher with Mod_Rewrite enabled. 

## Technical Overview

* Survey questions are configured in questions.json
* When a user first accesses the survey, all the questions are loaded into session storage
* As the user completes the survey, their responses are saved in session storage
* Loading questions, processing responses and generating summary results is all managed bvy the Survey class defined in survey.php
* Rendering of the survey is perfromed by collectResponses.php
* Rendering of the survey results is performed by viewResults.php
* Layout uses [Bootstrap](http://getbootstrap.com/) 4.0.0
* Rendering charts uses [Chart.js](https://www.chartjs.org/) 2.7.2

## License

This source code is released under the MIT license. Bootstrap and Chart.js are also released under the MIT license.

## Credits

* Atos and Worldline experts who have contributed to formulation of the quetsions and creation of the application
* [Bootstrap](http://getbootstrap.com/)
* [Chart.js](https://www.chartjs.org/)
* [Markus Spiske](https://unsplash.com/@markusspiske) for background image, published on [Unsplash](https://unsplash.com/)
