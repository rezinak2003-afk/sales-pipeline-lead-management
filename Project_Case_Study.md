# Project Case Study — Sales CRM & Lead Funnel

## Business problem
A small sales team can lose opportunities when lead stages, qualification notes and next follow-ups are scattered across messages or spreadsheets. This practice project demonstrates a structured way to organise a lead pipeline and focus follow-up effort.

## Solution built
- A tracker with 50 synthetic leads and business-oriented fields: source, stage, priority, estimated deal value, owner, last contact and next follow-up.
- Formula-driven overdue flags that compare the next follow-up date with `TODAY()`, while marking Won/Lost leads as closed.
- A dashboard showing total and open leads, overdue follow-ups, wins, pipeline value, won value, meetings, proposals and stage distribution.
- Funnel analysis with current stage counts and a clearly labelled simplified cumulative-reach estimate.
- Inbound/outbound call scripts, a follow-up email template and a ten-point ethical objection playbook.
- CSV template for practising field mapping into a CRM.

## Core metrics
- Open pipeline value = sum of estimated deal value for leads that are neither Won nor Lost.
- Won value = sum of estimated value for Won leads.
- Overdue follow-up rate = overdue open leads divided by all leads in the sample.
- Stage counts = count of leads whose current stage matches each stage.

## Tools and skills demonstrated
Excel formulas (`COUNTIF`, `COUNTIFS`, `SUMIFS`, `IF`, `IFERROR`), dropdown validation, conditional formatting, dashboard charts, sales communication, lead qualification, follow-up management and ethical objection handling.

## Data and limitations
All companies, contacts, deal amounts, stages, and notes are fictional. It is an Excel-based CRM practice simulation—not a live HubSpot/Zoho integration and not evidence of actual sales performance. Cumulative funnel reach is estimated from current stage ordering because no stage-history timestamps are included.

## Possible next iteration
Import the practice CSV into a free CRM account if an eligible plan is available; compare the import fields; record stage-change history and date stamps; then replace the simplified funnel estimate with true stage conversion metrics.
