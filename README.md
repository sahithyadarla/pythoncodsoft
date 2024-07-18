# pythoncodsoft
import json

class ToDoList:
    def _init_(self, filename='todo_list.json'):
        self.filename = filename
        try:
            with open(self.filename, 'r') as file
