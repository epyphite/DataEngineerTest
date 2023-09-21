Coding Test: Road Links Data Engineering
Objective:

Create a Dockerized Python application to process and load road links data into a PostgreSQL database. Visualize the processed data using a Python notebook.
Requirements:

    Docker
    Python 3.x
    PostgreSQL
    Pandas
    Matplotlib
    Jupyter Notebook

Task Details:

    File Processing:
        Write a Python script to read the given text file containing road links data.
        Parse each line to extract road_id, Direction, and polyline (a series of lat-long pairs).

    Database Loading:
        Create a PostgreSQL database and a table road_links using the provided SQL DDL.
        Use Python and an appropriate PostgreSQL driver (like psycopg2) to insert the parsed data into the road_links table.

    Dockerization:
        Create a Dockerfile that sets up an environment with Python, PostgreSQL, and all required packages.
        Write instructions in the README on how to build and run the Docker container to execute the file processing and database loading scripts.

    Data Visualization:
        Use Jupyter Notebook to connect to the PostgreSQL database.
        Create at least one plot to visualize the data using Matplotlib. You might plot things like:
            Number of road links per direction (1 or 0).
            Length distribution of the polylines (you may have to calculate this).

    Documentation:
        Write a README file explaining how to run all parts of the project, including building the Docker image, running the container, and executing the Jupyter Notebook.

    Code Versioning:
        Use Git for version control.
        Commit your code and documentation to a GitHub repository.

Evaluation Criteria:

    Correctness and completeness of the Python script and PostgreSQL database operations.
    Proper Dockerization of the application.
    Quality and relevance of the data visualization in the Jupyter Notebook.
    Quality of the code, including readability and adherence to best practices.
    Quality of the documentation in the README.
