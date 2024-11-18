```bash
安装conan2.0
pip install conan
```

```python
conan install . --build=missing -s build_type=Release  

cmake . --preset conan-release 
cmake --build . --preset conan-release 
```
