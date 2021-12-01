# Bosch Building Technologies - Ontology Central

The Bosch Building Technologies ontology model repository for commercial buildings.

## Overview

Welcome to **ontology central** the Bosch Building Technologies ontology repository for commercial buildings!

The repository contains the **Bosch Building Technologies** ontology models. The models can be found in the folder `com/bosch/bt`. The folder structure for each model is `{model-name}/{version}`. Each model consists of a set of *Azure Digital Twins models* see <http://aka.ms/ADTv2Models>) and a `MANIFEST.json` file. The manifest file describes the name and dependencies.

## Repository Content

> The ontology models in this repo are currently undergoing an update, to stay synchronized with the recent ("breaking") implementation of the first services. As a result, you may temporarily encounter broken links or sample code that have not yet been updated to match the newest deployment. Thank you for your patience while the repo is "under construction!"

The repository contains th following Bosch Building Technologies ontology models:

Ontology | Version | Description
--- | :-: | :--
:notebook: [**Foundation Ontology**](./com/bosch/bt/Foundation/2.0.0) | **2.0.0** | Base ontology model defines common concepts like the space topology structure, assets and (data) points.
:notebook: [**Fire Alarm Systems Ontology**](./com/bosch/bt/fire-alarm-systems/2.0.0) | **2.0.0** | Ontology model to describe a fire alarm system, consisting of panels, modules and detectors.
:notebook: [**HVAC Systems Ontology**](./com/bosch/bt/hvac-systems/2.0.0) | **2.0.0** | Ontology model for HVAC systems to describe entities like `AHU`, `VAV` and `Sensors`. It's used in the current HVAC System Insights Application.

## Contributors

Contact details of the authors and contributors see [NOTICE](NOTICE).

## Enjoy the models!

:mask: **Building Intelligence as a Service** Team 2021.

## License

Bosch Building ontology central is open-sourced under the `Apache-2.0` license. See the [LICENSE](LICENSE) file for details.
