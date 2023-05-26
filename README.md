valid `Class`, saves it (to the JSON file) and prints the `id`.  Valid classes are: BaseModel, User, State, City, Amenity, Place, Review. |

| **Usage** | **create <class name\>**|

| **-----** | **-----** |

| **show** | Prints the string representation of an instance based on the class name and `id`  |

| **Usage** | **show <class name\> <id\>** --or-- **<class name\>.show(<id\>)**|

| **-----** | **-----** |

| **destroy** | Deletes an instance based on the class name and `id` (saves the change into a JSON file).  |

| **Usage** | **destroy <class name\> <id\>** --or-- **<class name>.destroy(<id>)** |

| **-----** | **-----** |

| **all** | Prints all string representation of all instances based or not on the class name.  |

| **Usage** | By itself or **all <class name\>** --or-- **<class name\>.all()** |

| **-----** | **-----** |

| **update** | Updates an instance based on the class name and `id` by adding or updating attribute (saves the changes into a JSON file).  |

| **Usage** | **update <class name\> <id\> <attribute name\> "<attribute value\>"** ---or--- **<class name\>.update(<id\>, <attribute name\>, <attribute value\>)** --or-- **<class name\>.update(<id\>, <dictionary representation\>)**|

| **-----** | **-----** |

| **count** | Retrieve the number of instances of a class.  |

| **Usage** | **<class name\>.count()** |
