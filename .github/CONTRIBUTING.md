# Contributing to All The Things

Thank you for your interest in contributing! This guide will help you add your favorite learning resources to the list.

## How to Contribute

There are two ways to contribute:

### Option 1: Suggest a Resource (Easy - No Coding Required)

1. Go to the [Issues](https://github.com/yltw27/all-the-things/issues) tab
2. Click "New Issue"
3. Use the "Resource Suggestion" template
4. Fill in the details about your resource
5. Submit - We'll review and add it for you!

### Option 2: Submit a Pull Request (For GitHub Users)

1. **Fork the repository**
   - Click the "Fork" button at the top right of this page

2. **Clone your fork**
   ```bash
   git clone https://github.com/YOUR-USERNAME/all-the-things.git
   cd all-the-things
   ```

3. **Create a new branch**
   ```bash
   git checkout -b add-resource-name
   ```

4. **Add your resource to the appropriate table in README.md**

   Find the right category (AI & Machine Learning, Software Development, Product, Tech Trends, or Productivity) and add a new row:

   ```markdown
   | Type | Resource | Description | Recommended by |
   |------|----------|-------------|----------------|
   | Newsletter | [Resource Name](URL) | Brief description | [![@yourusername](https://github.com/yourusername.png?size=32)](https://github.com/yourusername) |
   ```

5. **Commit your changes**
   ```bash
   git add README.md
   git commit -m "Add [Resource Name] to [Category]"
   ```

6. **Push to your fork**
   ```bash
   git push origin add-resource-name
   ```

7. **Create a Pull Request**
   - Go to your fork on GitHub
   - Click "Compare & pull request"
   - Fill in the PR template
   - Submit!

## Upvoting Existing Resources

If you love a resource that's already listed, add your recommendation!

1. Find the resource in the table
2. In the "Recommended by" column, add your profile photo after existing ones:
   ```markdown
   [![@yltw27](https://github.com/yltw27.png?size=32)](https://github.com/yltw27) [![@yourusername](https://github.com/yourusername.png?size=32)](https://github.com/yourusername)
   ```

## Guidelines

**Resource Quality:**
- Only include resources you've personally used and found valuable
- Resources should be publicly accessible (free or paid)
- Avoid resources that are outdated or no longer maintained

**Formatting:**
- Keep descriptions concise (1-2 sentences max)
- Use consistent resource types: `Book`, `Newsletter`, `Website`, `Course`, `Video`, `Blog`, `Podcast`, etc.
- Check for duplicates before adding

**Content:**
- Resources should relate to: AI & Machine Learning, Software Development, Product Management, Tech Trends, or Productivity
- If you're unsure about the category, suggest it in the PR description

## What Happens After You Submit?

1. A maintainer will review your PR within a few days
2. We might ask for small changes (formatting, category, etc.)
3. Once approved, your contribution will be merged
4. Your GitHub profile photo will appear next to the resource!

## Code of Conduct

- Be respectful and constructive in all interactions
- Focus on resources that help people learn and grow
- Avoid self-promotion unless genuinely valuable to the community

## Questions?

Open an issue or reach out to [@yltw27](https://github.com/yltw27).

Thank you for helping build this community resource!
