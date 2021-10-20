pip wheel --wheel-dir dist .
rm dist/numpy-1.21.2-cp39-cp39-macosx_11_0_arm64.whl 
rm dist/simpleaudio-1.0.4-cp39-cp39-macosx_11_0_arm64.whl 
python -m twine upload --repository pypi dist/*    
