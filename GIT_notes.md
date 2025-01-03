GIT

это система контроля версий
---

возможности:
история кода
позволяет организовать работу нескольких разработчиков
---

СКВ бывают: распределенные и централизованные

централизованные системы: один сервер-репозиторий
распределенная: у каждого разработчика копия проекта и возможен обмен в произвольном порядке изменениями
---

терминология
репозиторий - хранилище
commit - фиксация изменений, конкретная версия репозитория
branch - альтернативная ветка развития кода
---

					 origin_project
			    -----------*------------
			   |						|  
		   copy_project				copy_project
			   |						|
			   *						* local commits
			   |						|
			   * local commits			*
			   |
			   *


git clone URL - make local copy of origin to PC
git add - add some files to copy
git commit - make commit local's changes to copy_project
git push - send local's changes from copy_project to origin_projects