# System Requirements

## 1. Purpose

This document defines the information, capabilities, data, and operating conditions required for the proposed system to capture fragmented project information, process heterogeneous data, normalize it into a common structure, and support intelligent linking of actual project progress with planned schedule activities.

The requirements are based on the identified problem of fragmented project data across multiple domains, subdomains, sources, formats, and storage locations.

## 2. System Scope

The proposed system is intended to support infrastructure project progress tracking by bringing together information from different project domains and data sources.

The system is expected to be capable of handling:

- Multiple project domains and subdomains
- Multiple data sources and storage locations
- Different file and data formats
- Structured and unstructured information
- Actual project progress information
- Planned schedule information
- Data processing and normalization
- Intelligent interpretation and schedule linking



## 3. Data Input Requirements

The system requires project information from different domains and subdomains.

### Domain and Subdomain Information

The system is expected to be able to associate incoming information with its relevant project domain and subdomain.



### Data Sources

The system is expected to be able to receive information from different sources and locations.

- Local folders
- Company servers
- SharePoint
- Google Drive
- Document Management Systems
- Databases
- Email attachments
- Cloud storage
- External systems through APIs


### Data Formats

The system is expected to support:

- Excel
- CSV
- PDF
- Word/DOCX
- PowerPoint/PPTX
- TXT
- Images
- Scanned documents
- Database records
- API responses
- Audio/transcribed information


## 4. Data Content Requirements

The incoming information should contain sufficient information to understand the project activity and its progress.

- Project name or identifier
- Domain
- Subdomain
- Activity description
- Activity ID, where available
- Location
- Planned start date
- Planned finish date
- Actual start date
- Actual finish date
- Current status
- Progress quantity
- Progress percentage
- Reporting date
- Contractor or responsible organization
- Supporting remarks or descriptions


## 5. Schedule Data Requirements

The system requires planned schedule information for schedule-linking activities.

The schedule data should contain:

- Project identifier
- Activity ID
- Activity name/description
- Activity hierarchy or level
- Discipline/domain
- Location
- Planned start date
- Planned finish date
- Baseline dates
- Planned quantity, where available
- Work package or related grouping
- Activity status

The system should be able to work with detailed schedule activities, including L5/L6 activities where such levels are available.

---

## 6. Functional Requirements

The system is expected to be capable of performing the following functions.

### Data Acquisition

The system is expected to obtain data from supported sources and locations.

### Data Identification

The system is expected to identify:

- Data source
- File/data format
- Project
- Domain
- Subdomain
- Relevant document or record

### Data Extraction

The system is expected to extract usable information from supported data formats.


- Tables and cells from spreadsheets
- Text and tables from documents
- Text from PDFs
- Text from scanned documents
- Records from databases

### Data Normalization

Information obtained from different sources should be converted into a common internal structure.


### Data Validation

The system is expected to identify incomplete, new, irreleveant information.


- Missing activity information
- Invalid dates
- Duplicate records
- Conflicting progress updates
- Missing source information

### Progress Interpretation

The system is expected to interpret project progress information from extracted data.


The system is expexted to identify information such as:

- Work type
- Discipline
- Activity
- Location
- Status
- Date

### Schedule Linking

The system is expected to support matching actual progress information with the planned schedule activity.

The matching process may consider:

- Activity description
- Domain
- Subdomain
- Location
- Equipment/item
- Dates
- Other relevant project attributes

### Result Generation

The system is expected to provide structured results that can be used for:

- Progress tracking
- Schedule updating
- Mismatch identification
- Reporting
- Analysis

---

## 7. AI and Intelligence Requirements

AI is primarily used where interpretation or understanding is required.

Potential AI supported functions include:

- Information extraction
- Entity identification
- Activity classification
- Semantic understanding of progress descriptions
- Similarity based activity matching
- Ambiguous information interpretation



