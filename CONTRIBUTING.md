# Contributor Guidelines

## 🚀 Quick Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/KDHarsh24/Face-Model.git
   cd Face-Model
   ```

2. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes** to the notebook

4. **Test locally** (optional but recommended):
   ```bash
   jupyter notebook face_recognition.ipynb
   ```

5. **Commit and push**:
   ```bash
   git add .
   git commit -m "feat: your descriptive message"
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** on GitHub

## 📋 Development Standards

### Notebook Structure
- Keep cells organized and well-documented
- Use markdown cells for explanations
- Include error handling in code cells
- Test all code paths before committing

### Code Quality
- Use meaningful variable names
- Add comments for complex operations
- Handle exceptions appropriately
- Release resources (cv2.VideoCapture, file handles)

### Commit Messages
Use conventional commit format:
- `feat:` - New features
- `fix:` - Bug fixes
- `docs:` - Documentation updates
- `refactor:` - Code refactoring
- `test:` - Testing improvements

## 🔍 Automated Checks

Every contribution is automatically checked for:
- ✅ Notebook format validation
- ✅ Code syntax correctness
- ✅ Dependency completeness
- ✅ Memory leak prevention
- ✅ Colab compatibility

## 🎯 Best Practices

### For Notebooks:
1. Always include `pip install` cell at the top
2. Use clear section headers with markdown
3. Test code with sample data
4. Include usage examples
5. Document model parameters

### For Face Recognition:
1. Use consistent video naming: `Video_<name>.mp4`
2. Implement proper error handling
3. Add progress indicators for long operations
4. Optimize for both CPU and GPU
5. Include data validation

## 🐛 Reporting Issues

When reporting bugs:
1. Use the issue template
2. Include error messages
3. Specify environment (Colab/local)
4. Provide minimal reproduction steps
5. Tag with appropriate labels

## 🚀 Feature Requests

For new features:
1. Check existing issues first
2. Describe the use case clearly
3. Consider backward compatibility
4. Propose implementation approach
5. Add relevant tags

## 📚 Resources

- [Google Colab Guide](https://colab.research.google.com/notebooks/intro.ipynb)
- [InsightFace Documentation](https://github.com/deepinsight/insightface)
- [OpenCV Python Tutorials](https://docs.opencv.org/master/d6/d00/tutorial_py_root.html)

## 🤝 Getting Help

- 💬 Open a discussion for questions
- 🐛 Create an issue for bugs
- 📧 Contact maintainers for urgent matters
- 📖 Check existing documentation first

## 🏆 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes for major contributions
- GitHub contributors graph
- Special mentions for significant improvements
