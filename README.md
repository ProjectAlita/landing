# landing

## API Updates

### Removed Endpoints
- All endpoints under the `AdminAPI` mode handler were removed.
- The `api/v1/storage.py` file was deprecated, removing all associated endpoints.

### Modified Request Parameters
- Replaced `integration_id` and `is_local` with `configuration_title` across multiple endpoints.

### Response Format Changes
- Adjusted error responses to include descriptive messages for S3 access issues.
Langing
