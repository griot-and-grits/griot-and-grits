# Griot & Grits – Public Artifact Preservation

Griot & Grits enables the preservation and sharing of **public artifacts**—such as stories, videos, documents, and historical materials—for communal access, discovery, and enrichment using AI-powered processing.

---

## Initial User Flows

### 1. Admin – Upload New Artifact

- Admins upload new artifacts (audio, video, documents, etc.) via the Griot & Grits admin portal.
- Uploaded artifacts are archived and processed to extract metadata and content.

### 2. User – Search & View Artifacts

- Users browse or search the Griot & Grits library for publicly available artifacts.
- Users can view, search, and experience documentary-style, AI-enhanced stories or historical records.

---

## Artifact Processing Pipeline

1. **Upload:**  
   Admin uploads a new artifact through the admin portal.

2. **Archive & Extract:**  
   - Artifact is archived via S3 storage.
   - Asynchronous jobs transcribe audio/video, extract key metadata (people, events, locations), and enrich the artifact with relevant public domain information.

3. **AI Enhancement:**  
   - Gaps in stories are filled using Generative AI to create richer, more contextual narratives.
   - Artifacts are formatted into documentary-style, searchable content for the public library.

4. **Discovery:**  
   - Users can search or filter stories by event, person, location, or historical context.
   - Retrieved stories are presented in an engaging, AI-enhanced format.

---

## Example Workflow

1. *Amelia* records her grandfather’s story and uploads the video.
2. The system:
   - Transcribes and extracts people, events, and locations.
   - Adds relevant public domain content to enrich the story.
   - Uses GenAI to fill in life story gaps.
   - Adds the completed, enhanced story to the public archival library.
3. *Connor* searches the Griot & Grits Library and discovers his family’s story, along with other documentary-style stories.

---

## Architecture

<img width="1584" height="1077" alt="PublicArchive" src="https://github.com/user-attachments/assets/9f141409-333d-4275-888c-5c301f94f3e4" />


- **Transcription Service**: Converts audio/video to text for metadata extraction.
- **GenAI**: Enhances content, fills narrative gaps.
- **S3**: Stores raw and processed artifacts.
- **MongoDB** Indexes metadata for fast, unstructured search

---

## Key Features

- **Automated Transcription & Metadata Extraction:** All media is transcribed and enriched for discovery.
- **AI-Driven Story Enhancement:** Public domain information and generative AI enhance the artifact experience.
- **Searchable Library:** Stories and artifacts can be searched and filtered by event, person, or context.
- **Secure & Scalable Architecture:** Built with modern backend, storage, and AI/LLM services.


---

**Griot & Grits** 2025
