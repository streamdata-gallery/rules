---
swagger: "2.0"
info:
  title: AWS Config API Describe Configuration Recorders
  version: 1.0.0
  description: Returns the details for the specified configuration recorders.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeConfigurationRecorders:
    get:
      summary: ' Describe Configuration Recorders '
      description: Returns the details for the specified configuration recorders
      operationId: describeConfigurationRecorders
      parameters:
      - in: query
        name: ConfigurationRecorderNames
        description: A list of configuration recorder names
        type: string
      responses:
        200:
          description: OK
      tags:
      - configuration rules
definitions: []
x-collection-name: AWS Config
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---