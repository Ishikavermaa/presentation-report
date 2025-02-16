# presentation-report
# Version Control with Subversion (SVN) and Mercurial (Hg)

This guide covers the basic usage of **Subversion (SVN)** and **Mercurial (Hg)**, providing commands, explanations, and references for practical usage.

---
## Subversion (SVN)

### 1. Installing SVN

**Linux/macOS:**
```sh
sudo apt update && sudo apt install subversion  # Debian-based systems
sudo yum install subversion  # RHEL-based systems
brew install subversion  # macOS
```

**Windows:**
- Download and install TortoiseSVN: [https://tortoisesvn.net/](https://tortoisesvn.net/)

### 2. Basic SVN Commands

#### a) Checking Out a Repository
```sh
svn checkout <repo_url> <local_dir>
```
Example:
```sh
svn checkout https://example.com/svn/myproject myproject
```
This clones the repository into `myproject` directory.

#### b) Adding Files to SVN
```sh
svn add <file_or_directory>
```
Example:
```sh
svn add newfile.txt
```
This stages `newfile.txt` for the next commit.

#### c) Committing Changes
```sh
svn commit -m "Commit message"
```
Example:
```sh
svn commit -m "Added a new feature"
```
Sends local changes to the repository.

#### d) Updating a Working Copy
```sh
svn update
```
Fetches the latest changes from the repository.

#### e) Checking Repository Status
```sh
svn status
```
Shows the status of modified, added, and untracked files.

#### f) Viewing Log History
```sh
svn log
```
Displays commit history.

---

## Mercurial (Hg)

### 1. Installing Mercurial

**Linux/macOS:**
```sh
sudo apt update && sudo apt install mercurial  # Debian-based systems
sudo yum install mercurial  # RHEL-based systems
brew install mercurial  # macOS
```

**Windows:**
- Download and install from [https://www.mercurial-scm.org/](https://www.mercurial-scm.org/)

### 2. Basic Mercurial Commands

#### a) Creating a New Repository
```sh
hg init <repo_name>
```
Example:
```sh
hg init myproject
```
Initializes a new repository in `myproject` directory.

#### b) Cloning a Repository
```sh
hg clone <repo_url>
```
Example:
```sh
hg clone https://example.com/hg/myproject
```
Copies the repository to the local system.

#### c) Adding Files to Mercurial
```sh
hg add <file_or_directory>
```
Example:
```sh
hg add newfile.txt
```
Stages `newfile.txt` for the next commit.

#### d) Committing Changes
```sh
hg commit -m "Commit message"
```
Example:
```sh
hg commit -m "Initial commit"
```
Records changes in the repository.

#### e) Pulling Latest Changes
```sh
hg pull -u
```
Fetches and updates the local repository with remote changes.

#### f) Checking Repository Status
```sh
hg status
```
Displays modified, added, and untracked files.

#### g) Viewing Log History
```sh
hg log
```
Shows commit history.

---

## Screenshots / Recordings

- **Subversion (SVN) Demo:** [Placeholder for screenshots or screen recording]
- **Mercurial (Hg) Demo:** [Placeholder for screenshots or screen recording]

For a more in-depth understanding, visit:
- SVN Official Documentation: [https://subversion.apache.org/](https://subversion.apache.org/)
- Mercurial Official Documentation: [https://www.mercurial-scm.org/](https://www.mercurial-scm.org/)

---
