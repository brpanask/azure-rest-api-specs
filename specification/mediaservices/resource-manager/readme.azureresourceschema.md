## AzureResourceSchema

These settings apply only when `--azureresourceschema` is specified on the command line.

### AzureResourceSchema multi-api

``` yaml $(azureresourceschema) && $(multiapi)
# include the azure profile definitions from the standard location
require: ../../../profiles/readme.md

output-folder: $(azureresourceschema-folder)/schemas

# all the input files across all versions
input-file:
  - Microsoft.Media/stable/2020-05-01/AccountFilters.json
  - Microsoft.Media/stable/2020-05-01/Accounts.json
  - Microsoft.Media/stable/2020-05-01/AssetsAndAssetFilters.json
  - Microsoft.Media/stable/2020-05-01/ContentKeyPolicies.json
  - Microsoft.Media/stable/2020-05-01/Encoding.json
  - Microsoft.Media/stable/2020-05-01/StreamingPoliciesAndStreamingLocators.json
  - Microsoft.Media/stable/2020-05-01/streamingservice.json
  - Microsoft.Media/stable/2020-05-01/Common.json
  - Microsoft.Media/stable/2018-07-01/AccountFilters.json
  - Microsoft.Media/stable/2018-07-01/Accounts.json
  - Microsoft.Media/stable/2018-07-01/AssetsAndAssetFilters.json
  - Microsoft.Media/stable/2018-07-01/ContentKeyPolicies.json
  - Microsoft.Media/stable/2018-07-01/Encoding.json
  - Microsoft.Media/preview/2020-02-01-preview/MediaGraphs.json
  - Microsoft.Media/stable/2018-07-01/StreamingPoliciesAndStreamingLocators.json
  - Microsoft.Media/stable/2018-07-01/streamingservice.json
  - Microsoft.Media/preview/2019-09-01-preview/MediaGraphs.json
  - Microsoft.Media/preview/2019-05-01-preview/AccountFilters.json
  - Microsoft.Media/preview/2019-05-01-preview/Accounts.json
  - Microsoft.Media/preview/2019-05-01-preview/AssetsAndAssetFilters.json
  - Microsoft.Media/preview/2019-05-01-preview/Common.json
  - Microsoft.Media/preview/2019-05-01-preview/ContentKeyPolicies.json
  - Microsoft.Media/preview/2019-05-01-preview/Encoding.json
  - Microsoft.Media/preview/2019-05-01-preview/StreamingPoliciesAndStreamingLocators.json
  - Microsoft.Media/preview/2019-05-01-preview/streamingservice.json
  - Microsoft.Media/stable/2018-07-01/Common.json
  - Microsoft.Media/stable/2015-10-01/media.json
  - Microsoft.Media/preview/2018-03-30-preview/Accounts.json
  - Microsoft.Media/preview/2018-03-30-preview/Assets.json
  - Microsoft.Media/preview/2018-03-30-preview/ContentKeyPolicies.json
  - Microsoft.Media/preview/2018-03-30-preview/Encoding.json
  - Microsoft.Media/preview/2018-03-30-preview/StreamingPoliciesAndStreamingLocators.json
  - Microsoft.Media/preview/2018-03-30-preview/streamingservice.json
  - Microsoft.Media/preview/2018-06-01-preview/Accounts.json
  - Microsoft.Media/preview/2018-06-01-preview/Assets.json
  - Microsoft.Media/preview/2018-06-01-preview/ContentKeyPolicies.json
  - Microsoft.Media/preview/2018-06-01-preview/Encoding.json
  - Microsoft.Media/preview/2018-06-01-preview/StreamingPoliciesAndStreamingLocators.json
  - Microsoft.Media/preview/2018-06-01-preview/streamingservice.json

```