# Docker Installation

Before starting, ensure you have the latest versions of git, docker and docker-compose installed on your machine.

## Step 1: Clone the repo

```
$ git clone https://github.com/tellform/docker_files.git
```

### Step 2: Setup TellForm Configuration

Create your `.env` file by copying the `.env.dist` file included in the repo and changing it to suit your deployment.

**Important**: You need to fill out all of the ENV variables in the "Mail Settings" section or your TellForm instance won't work.

### Step 3: Start your TellForm instance

```docker-compose up -d```

TellForm is now accessible on https://localhost
