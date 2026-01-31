### Its me, Jhunu!

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

from datetime import datetime
from enum import StrEnum


class JhunuFernandes:
    full_name = "Jhunu Fernandes Araujo"
    current_role = "Software Engineer"

    def greet(self):
        now = datetime.now()
        drink = ("Cofee", "Beer")[now.hour >= 12]
        print(f"Lets drink a {self.drink} someday!")


class Databases(StrEnum):
    POSTGRES = "Postgres"
    MONGO = "Mongo"
    DYNAMO = "Dynamo"
    REDIS = "Redis"


languages_and_frameworks = {
    "python": [
        "Flask", "FastAPI", "Airflow"
    ],
    "js": [
        "React"   
    ],
}


class Extras:
    also_work_with = ["RabbitMQ", "MQTT"]
    major_clouds = ["AWS", "GCP", "OCI"]
    current_project = "Sthali"  # see my repos
    
```

#### python utilities
- [docs-generator](https://github.com/jhunufernandes/python-docs-generator)
- [package-template](https://github.com/jhunufernandes/python-package-template)
- [github-actions](https://github.com/jhunufernandes/python-github-actions)

#### project-sthali
- [core](https://github.com/jhunufernandes/sthali-core)
- [crud](https://github.com/jhunufernandes/sthali-crud)
- [auth](https://github.com/jhunufernandes/sthali-auth)
- [backend](https://github.com/jhunufernandes/sthali-backend)
- [scheduler](https://github.com/jhunufernandes/sthali-scheduler)
