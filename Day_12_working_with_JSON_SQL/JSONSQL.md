**JSON/SQL**



\-> JSON (JavaScript Object Notation) is a lightweight, text-based data-interchange format used to store and transmit structured data.



\-> API respond in JSON format which is parsed by different programming languages.



\-> SQL -> Structured Query Language

&#x09;-> get from database



\-> import pandas as pd

\-> to read the json dataset

&#x09;-> pd.read\_json("<file\_path>")





\-> for the sql files

&#x09;-> run the sql files on a database

&#x09;-> install the library to connect python to database

&#x09;	-> import sqlalchemy as db



&#x09;	engine = db.create\_engine(

&#x20;   			"postgresql://username:password@localhost:5432/database\_name"

&#x09;	)

&#x09;-> pd.read\_sql\_query("<sql\_query>" , <connection\_object>)

