# ansible-make-datasets
this ansible playbook allows you to download xeno-canto MP3 records and extract audio features

usages :

For generate training dataset
ansible-playbook playbook-make-training-datasets.yml  -e root_dir=somepath

For generate test dataset
ansible-playbook playbook-make-test-datasets.yml  -e root_dir=somepath

