 ###Problem to Solution Mapping


 ##Purpose
 This document maps the key problems identified from the SIH26122 problem statement to corresponding components of the solution.
 The objective is to show how each proposed feature or system component directly addresses a specific problem. The mapping provides the structured view of reasoning  behind the proposed solution.

 

 ##Problem To Solution Mapping

 | Problem | Why It Occurs | Proposed Solution | Expected Outcomes |
 |---|---|---|---|
 | Actual progress data is fragmented across disciplines and contractors. | Teams use separate daily reports, site diaries, spreadsheets, and verbal updates. | Create a unified platform to ingest and consolidate data from all disciplines and contractors. | A single, complete view of actual project progress. |
 | Progress reports are delayed. | Updates are collected manually and often reach planners days or weeks after execution. | Provide real-time reporting through a conversational and voice-based time agent. | Faster schedule updates and earlier visibility of delays. |
 | Input formats are inconsistent. | Each discipline and contractor follows its own reporting template, terminology, and cadence. | Use intelligent document ingestion and normalization for text, spreadsheets, PDFs, and scanned diaries. | Consistent, structured activity data regardless of input format. |
 | L5/L6 activity start and end times are not captured reliably. | Supervisors lack a low-friction method to record precise execution events at the work site. | Allow supervisors to log activity starts and completions using natural language or voice. | More accurate activity-level actual dates and durations. |
 | Field descriptions do not match schedule activity names. | Workers use practical or discipline-specific terms, while the baseline uses formal WBS terminology. | Apply fuzzy matching and language-based activity classification against the schedule. | Reliable links between field updates and the correct planned activity. |
 | Field work is more granular than the baseline plan. | Execution is often split into smaller tasks that are not represented as separate schedule nodes. | Detect granularity mismatches and propose links or new activities for planner review. | Fewer dropped updates and better alignment between execution and planning. |
 | Manual reconciliation with the baseline schedule is slow and error-prone. | Planners must compare multiple sources and enter actual dates by hand. | Automate extraction, validation, schedule linking, and near-real-time PMIS updates. | Reduced planning effort, fewer data-entry errors, and shorter update cycles. |
 | Progress data lacks confidence and traceability. | Updates may be ambiguous, incomplete, or altered without a clear record of their source. | Store confidence scores, source references, timestamps, user identity, and an audit trail for every update. | Reviewable, accountable, and trustworthy schedule data. |
 | Delay and performance analytics use poor-quality data. | Late, incomplete, and unstructured actuals undermine forecasting and risk analysis. | Build a clean, discipline-tagged actual-progress dataset for analytics and forecasting. | More accurate productivity analysis, delay detection, risk identification, and forecasts. |
 | Project execution knowledge is lost after project closure. | Real durations, bottlenecks, and recurring delay causes remain in personal notes or scattered files. | Maintain a queryable historical repository of execution events, causes, durations, and productivity patterns. | Institutional memory that improves future planning and decision-making. |

