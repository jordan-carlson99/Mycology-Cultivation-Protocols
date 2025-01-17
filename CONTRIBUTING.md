# Contribution guidelines

## Overview

This document outlines the standards and processes for contributing to the Mushroom Cultivation Protocols Library. Our goal is to create a high-quality, reproducible, and well-documented collection of cultivation techniques that benefit the broader mycology community.

## Core Principles

1. **Reproducibility:** All protocols must be detailed enough to be reproduced by others
2. **Safety:** Comprehensive safety information is mandatory
3. **Verification:** All procedures must be verified and sourced
4. **Standardization:** Follow provided templates and formatting
5. **Open Access:** Content must be freely available and shareable
6. **Honesty:** Authors should not omit any information or provide, knowingly, inaccurate information

## File Structure

```
├── protocols/
│   ├── agar-work/
│   ├── spawn/
│   ├── fruiting/
│   ├── liquid-culture/
│   └── general/
├── general-information/
│   ├── storage/
│   ├── safety/
│   ├── best-practices/
│   └── general/
├── templates/
│   ├── protocol-template/
│   │   ├── protocol-name\[tag].md
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── data/
│   │   │   └── sources/
│   └── protocol-template-standards/
├── LICENSE
├── CONTRIBUTING.md
└── README.md
```

### Protocol file structure

```
├── protocol-name\[tag1]\[tag2].md
├── assets/
│ ├── images/
│ ├── data/
│ └── sources/
```

### 1. Initial Submission

1. Fork the repository
2. Create a new branch: `git checkout -b protocol/your-protocol-name`
3. Use the standard template
4. Place files in correct directory structure
5. Submit pull request

### 2. Required Documentation

All submissions must include:

- Completed protocol template with all required fields
- Images of critical steps
- Verifiable references
- Complete safety information
- Growth parameters for at least one species

### 3. Formatting Requirements

- Use Markdown formatting
- Follow file naming convention: `protocol-name[tag1][tag2].md`
- Image format: PNG or JPEG, max 5MB per image
- Tables must use standard Markdown syntax
- Use SI units with imperial in parentheses

### 4. Quality Standards

#### Required for Acceptance

1. **Completeness**
   - All required sections filled out
   - No placeholder content
   - Complete safety information
   - Full materials list with quantities
2. **Verification**
   - At least one complete cycle documented
   - Growth parameters verified
   - Sources cited properly
   - Success indicators documented
3. **Safety**
   - Saftey procedures
   - Proper containment procedures
   - Disposal requirements
4. **Documentation**
   - Clear, focused photos of critical steps
   - Quality indicators described
   - Version control maintained

#### Additional Quality Guidelines

- Use clear, concise language
- Provide specific measurements
- Include common failure points
- Document optimization attempts (if any)

### 5. Peer Review Process

#### Review Requirements

1. **Technical Review**
   - Technical accuracy
   - Completeness check
   - Reference verification
2. **Format Review**
   - Template compliance
   - Image quality
   - Formatting accuracy
   - File structure

#### Review Process

1. Automated checks / linting run on submission
2. Two peer reviewers or one designated moderator must approve
3. Maintainer final review
4. Changes requested or merged

### 6. Updating Protocols

#### Version Control

- Follow semantic versioning
- Document all changes in changelog
- Update last modified date
- Maintain backwards compatibility when possible

#### Update Process

1. Create new branch from main
2. Make changes
3. Update version number
4. Submit pull request
5. Go through review process

### 7. Removal Requests

#### Grounds for Removal

- Safety concerns
- Proven inaccuracies
- Copyright violations
- Duplicate content
- Abandoned/unmaintained protocols

#### Removal Process

1. Submit removal request issue
2. Detail reasons for removal
3. Maintainer review
4. Decision implementation

### 8. Community Guidelines

#### Communication

- Be respectful and professional
- Focus on technical aspects
- Provide constructive feedback
- Document discussion outcomes

#### Collaboration

- Share improvements
- Report issues promptly
- Help review submissions
- Maintain documentation

## Review Checklist

### Initial Submission Review

- [ ] Follows template structure
- [ ] All required sections completed
- [ ] References properly formatted
- [ ] Images included and properly formatted
- [ ] Proper file location and naming
- [ ] Markdown formatting

### Technical Review

- [ ] Protocol is reproducible
- [ ] Safety measures adequate
- [ ] Growth parameters verified
- [ ] References checked
- [ ] Success indicators clear

### Final Review

- [ ] Community feedback addressed
- [ ] Version number appropriate
- [ ] Changelog updated
- [ ] Documentation complete
- [ ] Review comments resolved
- [ ] Final formatting check
- [ ] Ready for merge

## Contact

- Create an issue for questions
- Join discussion forum
- Contact maintainers

Remember: Quality over quantity. Take time to create well-documented, verified protocols that will benefit the community.
