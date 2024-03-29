
# About Me.

```python
from typing import Tuple, List, Dict

class Travis:
    pass

class Attributes(Travis):
    @property
    def contact(self) -> Tuple[str, str, str]:
        email    = "lanceurfloko@gmail.com"
	    
	    return email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['French', 'Spanish', 'English']
        age   = 15
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['web', 'js', 'godot'],
            'learning'    : ['c', 'c++', 'c#', 'java']
        }
        specialities  = ['web/app dev', 'software engineer', 'gamedev']
        ide           = ['vscode']
        pc            = {
            'Windows': {
                'custom': {
                    'os': 'Win 10',
                    'ram': '10gb',
                    'gpu': 'nvidia GTX'
                }
            }
        }

	
