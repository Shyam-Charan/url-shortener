# Architecture

## Components

### API Layer
Accepts long URLs and returns shortened versions.

### Hashing Module
Generates unique short codes from URLs.

### Storage Layer
Maps short codes to original URLs.

## Data Flow

Long URL → Hashing Module → Short Code → Storage → Redirect
