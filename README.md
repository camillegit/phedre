# phedre
A teacher assistant that gives daily lesson based on personnal pdf book library

## Architecture

### TOC parser
A script that read pdf, parse the TOC to extract a tree of the chapters and subchapters.
Missing and bugs : missing scans, bugs some artifacts (headers)

### Graph
Use the TOC of all books to create progressive learning graph

### Lesson generation
Picks a node in the graph and generate a lesson from the next node to learn, giving some reminders of past nodes. Asking questions to verify learning is effective.

### Test to speech and UX
Transcribe text to speech, and fluid user experience
