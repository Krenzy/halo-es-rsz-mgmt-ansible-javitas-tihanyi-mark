This Ansible is made for fix the previous homework.

Before run roles, please run the "playbook_user-login.yml" for correct user
login.

The file structure is next:
.
├── ansible.cfg
├── Change_pw-role
│   ├── handlers
│   │   └── main.yml
│   ├── meta
│   │   └── main.yml
│   ├── README.md
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
├── inventory
├── NFS_share-role
│   ├── handlers
│   │   └── main.yml
│   ├── meta
│   │   └── main.yml
│   ├── README.md
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
├── NFS_to_fstab-role
│   ├── handlers
│   │   └── main.yml
│   ├── meta
│   │   └── main.yml
│   ├── README.md
│   ├── tasks
│   │   └── main.yml
│   └── vars
│       └── main.yml
├── playbook_user-login.yml
└── README.md
