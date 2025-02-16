```python

from typing import Tuple, List, Dict

class Tekky:
    pass

class Attributes(Tekky):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/your_telegram_username"
        github   = "github.com/your_github_username"
        email    = "your_email@example.com"
     
        return telegram, github, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['Polish', 'English']
        age   = 17
  
        return langs, age
 
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str, Dict[str, Dict[str, str]]]]:
        langs = {
            'expert'      : ['Python'],
            'intermediate': ['JS'],
        }
        specialities  = ['Web Development', 'Scripting', 'Automation']
        ide           = ['VSCode']
        pc            = {
            'Windows': {
                'Acer Nitro 5': {
                    'processor': 'Core i5',
                    'ram'      : '8GB',
                    'gpu'      : 'RTX 3050ti'
                }
            }
        }

        return langs, specialities, ide, pc
```


