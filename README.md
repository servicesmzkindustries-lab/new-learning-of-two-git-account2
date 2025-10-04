# new-learning-of-two-git-account2

import subprocess

def git_branch():
    """Current branch check"""
    return subprocess.getoutput("git branch --show-current")

# Example usage
if __name__ == "__main__":
    print("Branch:", git_branch())

hi
fe