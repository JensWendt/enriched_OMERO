# "enriched" OMERO
This repo contains the documentation for the OMERO instance [omero-nfdi.uni-muenster.de](https://omero-nfdi.uni-muenster.de).

The goal is to have a public OMERO for the community with all possible (relevant)plugins installed as sandbox to test plugins/scripts in development, as well as have an instance to test workflows against a broad spectrum of image data including metadata.

## How to get in
The aim is to make this as open as possible.
To achieve this we adopted the [omero-signup](https://github.com/ome/omero-signup) plugin that is also being used at the [official Demo instance](https://demo.openmicroscopy.org) of the OME consortium.
Users can self-register and will get placed in the `Demo` group.

The `Demo` group also contains the Public User, making it accessible for everyone even withouth an account. We try to keep all the sample image data in this open group.

For developers who need deeper access to the VM via ssh, please contact us so we can arrange the details.

## How to get in contact
This instance is hosted by [NFDI4Bioimage](https://nfdi4bioimage.de).
If you have any questions that go beyond the scope of this repo, get in contact with us via our [Helpdesk](https://nfdi4bioimage.de/helpdesk) or helpdesk@nfdi4bioimage.de.

## Technical specifications
The instance is running on a virtual machine on the Openstack of University Münster.
The Ubuntu 24.04 has 8 VCPUs, 32GB RAM and 50GB HDD. <br>Multiple FileShares are/can be mounted, including S3 buckets.

## Plugins
This is a list of installed and wished-for plugins. We try to keep them up to date and at least test the basic functionality. If you find bugs or want to see other plugins or configurations on the instance please create an Issue.

| Name                    | Installation Status | Version | Notes |
|-------------------------|---------------------|---------|-------|
| Autotag                 | Tested              | 4.1.0   | — |
| Figure                  | Tested              | 7.2.1   | — |
| iViewer                 | Tested              | 0.16.0  | — |
| omero-cli-duplicate     | Tested              | 0.4.0   | — |
| omero-cli-zarr          | Installed           | 0.5.5   | — |
| omero-rdf               | Installed           | 0.6.1   | — |
| omero-web-zarr          | Installed           | 0.1.1   | — |
| OpenLink                | Tested              | 2.1.2   | — |
| Parade                  | Installed           | 0.2.4   | — |
| TagSearch               | Tested           | 4.3.0   | — |
| rocrate                 | Installed           | 0.13.0  | — |
| omero-zarr-pixel-buffer | Installed           | 0.7.0   | — |
| omero-vitessce          | Tested           | 1.2.4   | — |
| omero-mapr              | Installed              | 0.5.3   | — |
| omero.forms             | Installed             | 1.1.0   | — |
| omero-ontop-mappings    | Tested           | —       | — |
| omero-signup            | Tested              | 0.3.3   | — |
| omero-scripts           | Tested              | 5.9.0   | — |
**SOON TO COME**
| Parade-crossfilter      |              | —       | Install from pip may not work because of Django 4. Install from GitHub repo: https://github.com/will-moore/parade-crossfilter |
| omero-demo-cleanup |      |    | —|

