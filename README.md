# New project to test our operator
oc new-project prodset

# Create the operator scaffold
operator-sdk new --type ansible --kind Foo --api-version foo.cvicens.com/v1alpha1 ansible-operator --generate-playbook --skip-git-init
cd ansible-operator 

