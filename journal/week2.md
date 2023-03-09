# Week 2 — Distributed Tracing

# Week 2 — Distributed Tracing

## Instrument our backend flask application to use Open Telemetry (OTEL) with Honeycomb.io as the provider
- Instrumented - Backend 
 
Connecting to the Honeycomb was just fixed by `exporting` the `key`

Proof of the Instrumentation with Honeycomb 
## Verification Image

![Instrumntation](assests/honeycomb-receiving.png)


Adding span for the Mock-data in Honeycomb for the Home Page activities 
## Verification Image

![home-activities-mock-data](assests/honeycomb-mockdata.png)


<hr>

## Run queries to explore traces within Honeycomb.io

Running various querries was done using the reference from https://docs.honeycomb.io/getting-data-in/opentelemetry/python/ to `acquiring the Tracer` and for `Query to trace` 


## Verification Image
### ISOFormat Query
![Query](assests/query1.png)


### Adding Span for Result Length 
![Query ](assests/query2.png)


<hr>

## Instrument AWS X-Ray into backend flask application

- Setup X-Ray Traces 

## Verification Image
![Setup X-Ray-Traces ](assests/xray1.png)

<hr>


## X-Ray Instrumented

## Verification Image
![AWS X-Ry INstrumented ](assests/xray2.png)

<hr>

## Add X-Ray sub-segment
![AWS X-Ry sub-segmemt](assests/xray-subsegmemt.png)


<hr>

## Cloudwatch Instrumented
## Verification Image
![AWS Cloudwatch Log ](assests/cludwatch-logs.png)
<hr>


## Integrate Rollbar for Error Logging


## Verification Image
![Rollbar Integration2 ](assests/rollbar.png)


<hr>
