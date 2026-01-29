# Sales Pipeline Dashboard – Asana & Power BI Integration
## Project Overview

This project involved building a Power BI sales dashboard integrated with Asana to provide visibility into lead progression, conversion performance, and pipeline value. The dashboard translates operational task data from Asana into structured analytical insights for sales monitoring and decision support.

## Business Context

Asana was used to manage sales activities and track leads through multiple stages using sections and custom fields. However, the operational structure introduced challenges for analytical reporting, including duplicated task records, mixed task hierarchies, and inconsistent field usage. The objective was to create a reliable analytical layer without changing the source system.

## Data & Modelling Approach

Source system: Asana (tasks, sections, custom fields)

Analytics platform: Power BI

## Key modelling decisions:

Filtered data to parent-level tasks only to represent leads

Resolved duplication caused by custom fields and multi-value attributes

Normalised sales attributes into a lead-level analytical table

Implemented consistent stage ranking logic to ensure valid funnel analysis

Preserved operational flexibility in Asana while enforcing analytical consistency in Power BI

## Key Features

Lead funnel analysis from enquiry to conversion

Conversion counts and cumulative stage progression

Open pipeline and proposal value tracking

Time-based analysis using a calendar dimension

Duplicate-safe aggregation of estimated values

Clear distinction between leads and subtasks

## Challenges Addressed

Data duplication caused by custom fields and multi-value attributes

Mismatch between operational and analytical grain (tasks vs leads)

Inconsistent stage definitions across sections and status fields

Over-counting risks in pipeline and funnel metrics

These were resolved through careful data shaping, stage ranking logic, and task-level de-duplication.

## Outcome

The final dashboard provides a single, reliable view of the sales pipeline while remaining fully aligned with Asana’s operational workflows. It enables stakeholders to monitor lead volume, conversion performance, and pipeline value with confidence.

## Tools & Skills Demonstrated

Power BI (data modelling, DAX, funnel and pipeline metrics)

Power Query (data shaping, de-duplication, pivoting)

Analytical modelling from operational task systems

Business logic validation and data quality handling
