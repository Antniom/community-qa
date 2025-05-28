# MoodleGPT Pro - Community Q&A Database

Welcome to the community-maintained question and answer database for **MoodleGPT Pro**!

## 📊 Database Stats

- **Total Questions:** 3
- **Last Updated:** 2025-05-28T01:15:30.388Z
- **Version:** 1

## 🤝 How to Contribute

### Adding New Questions

1. **Fork this repository**
2. **Edit `qa-database.json`** 
3. **Add your question** following the format below
4. **Submit a Pull Request**

### Question Format

```json
{
  "id": "unique-identifier",
  "question": "Your question text here?",
  "answers": ["Option A", "Option B", "Option C", "Option D"],
  "answer": "Correct answer",
  "type": "multiple_choice|true_false|fill_blank",
  "subject": "category/subject",
  "difficulty": "easy|medium|hard", 
  "source": "textbook|course|community|other",
  "dateAdded": "2025-05-28T00:00:00Z",
  "contributors": ["your-github-username"],
  "verified": false
}
```

### Quality Guidelines

- ✅ Questions should be clear and unambiguous
- ✅ Provide accurate and verified answers
- ✅ Use proper Portuguese grammar (primary language)
- ✅ Include subject/category for organization
- ✅ Test your questions before submitting

## 📋 Question Categories

- **Engineering** - Technical engineering questions
- **Mathematics** - Math and calculations
- **Science** - Physics, chemistry, biology
- **Technology** - IT and software-related
- **General** - General knowledge questions

## 🔧 Integration with MoodleGPT Pro

This database automatically syncs with the MoodleGPT Pro extension when users enable **Community Database Sync** in settings.

### For Extension Users:
1. Open MoodleGPT Pro settings
2. Enable "Community Database Sync"
3. Set sync frequency (daily recommended)
4. Questions from this repository will be available in your extension

### For Developers:
- API Endpoint: `https://api.github.com/repos/moodlegpt/community-qa/contents/qa-database.json`
- Format: JSON with base64 encoding
- Rate Limit: GitHub API limits apply

## 📝 License

This database is open source and available under the MIT License. By contributing, you agree to make your questions available to the community.

## 🙋‍♂️ Support

- **Issues:** Report problems or suggest improvements via GitHub Issues
- **Questions:** Ask questions in GitHub Discussions
- **Extension Support:** Contact MoodleGPT Pro support team

---

**Made with ❤️ by the MoodleGPT Pro community**
