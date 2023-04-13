# file_operations.py
def create_directory(directory):
    """Write text to a file"""
    try:
        directory = safe_join(working_directory, directory)
        if not os.path.exists(directory):
            os.makedirs(directory)
        return "Directory created successfully."
    except Exception as e:
        return "Error: " + str(e)

# commands.py


...
