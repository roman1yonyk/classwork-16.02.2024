class AcademicDiscipline:
    def __init__(self, name, topic, goals, structure, teaching_methods):
        self.name = name
        self.topic = topic 
        self.goals = goals
        self.structure = structure
        self.teaching_methods = teaching_methods
    def display_info(self):
        print("software_engineering:", self.name)
        print("programming:", self.topic)
        print("create_programs:", self.goals)
        print("program_reliability:", self.structure)
        print("discipline:",self.teaching_methods)
    software_engineering_discipline = ("Інженерія програмного забезпечення","проектування та розробка програмних систем",
                                       "Навчити принципам та практиці розробки програмного забезпечення",
                                       "Лекції, практичні заняття, лабораторні роботи", ["Експерименти","Проекти","Код-рев'ю"])
    software_engineering_discipline.display_info()
