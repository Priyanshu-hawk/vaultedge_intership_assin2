## API USAGE
1. API works on POST request only.
2. JSON data is required to be sent in the request body with following format:

```
{
    "file_path" : "FILE_PATH/FILE_NAME.pdf",<br>
    "angle_of_rotation" : ROTATION_ANGLE,<br>
    "page_number" : PAGE_NUMBER,<br>
}
```

3. API returns a JSON response with the following format:

```
{
    "Success": "File rotated successfully",
    "Rotated_File_path": "FILE_PATH/FILE_NAME_rotated.pdf"
}
```