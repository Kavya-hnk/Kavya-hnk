
pytest commands:
python -m pytest tests\ -s
coverage run -m pytest maincode\
coverage report -m tests\

file join:
path = os.path.dirname(__file__)
resource_path = os.path.join(path[:-29], "resources")
file_path = os.path.join(resource_path, 'test_file.txt')

git commands:
git checkout develop
git pull -p
git checkout feature_branch
git merge develop
git push origin feature_branch
