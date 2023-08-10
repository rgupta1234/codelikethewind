Last login: Fri Aug 20 08:51:22 on ttys000
rgupta@rgupta-mac ~ % ls
Applications	Desktop		Documents	Downloads	Library		Movies		Music		Pictures	Public		VirtualBox VMs
rgupta@rgupta-mac ~ % cd Documents 
rgupta@rgupta-mac Documents % ls
L-What's%20New%20in%20OpenShift%20Container%20Platform%204.7.pptx_0.odp	keycloak
WebEx									openshift
accounts								personal
expenses								principal
rgupta@rgupta-mac Documents % cd keycloak 
rgupta@rgupta-mac keycloak % ls
20210808_073729.jpeg						Loan Estimate Package.pdf
20210809_094102.jpeg						keycloak-15.0.1
Application Package.pdf						keycloak-15.0.1.zip
Keycloak-Identity-and-Access-Management-for-Modern-Applications
rgupta@rgupta-mac keycloak % cd Keycloak-Identity-and-Access-Management-for-Modern-Applications 
rgupta@rgupta-mac Keycloak-Identity-and-Access-Management-for-Modern-Applications % ls
LICENSE		README.md	ch13		ch2		ch4		ch5		ch6		ch7		ch9
rgupta@rgupta-mac Keycloak-Identity-and-Access-Management-for-Modern-Applications % cd ch2
rgupta@rgupta-mac ch2 % ls
backend		frontend
rgupta@rgupta-mac ch2 % cd frontend 
rgupta@rgupta-mac frontend % ls
Dockerfile		app.js			index.html		node_modules		package-lock.json	package.json
rgupta@rgupta-mac frontend % npm install

up to date, audited 55 packages in 659ms

1 package is looking for funding
  run `npm fund` for details

found 0 vulnerabilities
npm notice 
npm notice New minor version of npm available! 7.20.5 -> 7.21.0
npm notice Changelog: https://github.com/npm/cli/releases/tag/v7.21.0
npm notice Run npm install -g npm@7.21.0 to update!
npm notice 
rgupta@rgupta-mac frontend % npm start

> keycloak-example-app@0.0.1 start
> node app.js

zsh: killed     npm start
rgupta@rgupta-mac frontend % clear

rgupta@rgupta-mac frontend % oc login https://api.cluster-t68tn.t68tn.sandbox977.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-t68tn.t68tn.sandbox977.opentlc.com/oauth/token/request
rgupta@rgupta-mac frontend % oc login --token=sha256~kfaZnWY0--sPjUib5IgmYJG2s7lH2864UItRn8iy080 --server=https://api.cluster-t68tn.t68tn.sandbox977.opentlc.com:6443 
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-t68tn.t68tn.sandbox977.opentlc.com:6443" as "admin" using the token provided.

You have access to 70 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac frontend % clear
























rgupta@rgupta-mac frontend % oc get nodes -o wide
NAME                                         STATUS   ROLES    AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                       KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-136-67.us-east-2.compute.internal    Ready    master   16h   v1.21.1+051ac4f   10.0.136.67    <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-153-232.us-east-2.compute.internal   Ready    worker   16h   v1.21.1+051ac4f   10.0.153.232   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-164-238.us-east-2.compute.internal   Ready    worker   16h   v1.21.1+051ac4f   10.0.164.238   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-165-219.us-east-2.compute.internal   Ready    master   16h   v1.21.1+051ac4f   10.0.165.219   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-217-104.us-east-2.compute.internal   Ready    master   16h   v1.21.1+051ac4f   10.0.217.104   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
rgupta@rgupta-mac frontend % oc whoami
admin
rgupta@rgupta-mac frontend % oc get nodes -o wide
NAME                                         STATUS   ROLES    AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                       KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-136-67.us-east-2.compute.internal    Ready    master   19h   v1.21.1+051ac4f   10.0.136.67    <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-153-232.us-east-2.compute.internal   Ready    worker   19h   v1.21.1+051ac4f   10.0.153.232   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-164-238.us-east-2.compute.internal   Ready    worker   19h   v1.21.1+051ac4f   10.0.164.238   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-165-219.us-east-2.compute.internal   Ready    master   19h   v1.21.1+051ac4f   10.0.165.219   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
ip-10-0-217-104.us-east-2.compute.internal   Ready    master   19h   v1.21.1+051ac4f   10.0.217.104   <none>        Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)   4.18.0-305.10.2.el8_4.x86_64   cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
rgupta@rgupta-mac frontend % oc describe node ip-10-0-153-232.us-east-2.compute.internal
Name:               ip-10-0-153-232.us-east-2.compute.internal
Roles:              worker
Labels:             beta.kubernetes.io/arch=amd64
                    beta.kubernetes.io/instance-type=m5.2xlarge
                    beta.kubernetes.io/os=linux
                    failure-domain.beta.kubernetes.io/region=us-east-2
                    failure-domain.beta.kubernetes.io/zone=us-east-2a
                    kubernetes.io/arch=amd64
                    kubernetes.io/hostname=ip-10-0-153-232
                    kubernetes.io/os=linux
                    node-role.kubernetes.io/worker=
                    node.kubernetes.io/instance-type=m5.2xlarge
                    node.openshift.io/os_id=rhcos
                    topology.ebs.csi.aws.com/zone=us-east-2a
                    topology.kubernetes.io/region=us-east-2
                    topology.kubernetes.io/zone=us-east-2a
Annotations:        csi.volume.kubernetes.io/nodeid: {"ebs.csi.aws.com":"i-03cec6b3ff2e3f45e"}
                    machine.openshift.io/machine: openshift-machine-api/cluster-t68tn-62ll9-worker-us-east-2a-qctxg
                    machineconfiguration.openshift.io/controlPlaneTopology: HighlyAvailable
                    machineconfiguration.openshift.io/currentConfig: rendered-worker-9d6c6443dc60d5f0bdfec299f03ee95d
                    machineconfiguration.openshift.io/desiredConfig: rendered-worker-9d6c6443dc60d5f0bdfec299f03ee95d
                    machineconfiguration.openshift.io/reason: 
                    machineconfiguration.openshift.io/state: Done
                    volumes.kubernetes.io/controller-managed-attach-detach: true
CreationTimestamp:  Mon, 23 Aug 2021 14:45:21 -0500
Taints:             <none>
Unschedulable:      false
Lease:
  HolderIdentity:  ip-10-0-153-232.us-east-2.compute.internal
  AcquireTime:     <unset>
  RenewTime:       Tue, 24 Aug 2021 10:10:10 -0500
Conditions:
  Type             Status  LastHeartbeatTime                 LastTransitionTime                Reason                       Message
  ----             ------  -----------------                 ------------------                ------                       -------
  MemoryPressure   False   Tue, 24 Aug 2021 10:05:30 -0500   Mon, 23 Aug 2021 14:45:21 -0500   KubeletHasSufficientMemory   kubelet has sufficient memory available
  DiskPressure     False   Tue, 24 Aug 2021 10:05:30 -0500   Mon, 23 Aug 2021 14:45:21 -0500   KubeletHasNoDiskPressure     kubelet has no disk pressure
  PIDPressure      False   Tue, 24 Aug 2021 10:05:30 -0500   Mon, 23 Aug 2021 14:45:21 -0500   KubeletHasSufficientPID      kubelet has sufficient PID available
  Ready            True    Tue, 24 Aug 2021 10:05:30 -0500   Mon, 23 Aug 2021 14:46:03 -0500   KubeletReady                 kubelet is posting ready status
Addresses:
  InternalIP:   10.0.153.232
  Hostname:     ip-10-0-153-232.us-east-2.compute.internal
  InternalDNS:  ip-10-0-153-232.us-east-2.compute.internal
Capacity:
  attachable-volumes-aws-ebs:  25
  cpu:                         8
  ephemeral-storage:           125293548Ki
  hugepages-1Gi:               0
  hugepages-2Mi:               0
  memory:                      32448468Ki
  pods:                        250
Allocatable:
  attachable-volumes-aws-ebs:  25
  cpu:                         7500m
  ephemeral-storage:           115470533646
  hugepages-1Gi:               0
  hugepages-2Mi:               0
  memory:                      31297492Ki
  pods:                        250
System Info:
  Machine ID:                             ec213a08cde82bb652a720c834f01c8c
  System UUID:                            ec213a08-cde8-2bb6-52a7-20c834f01c8c
  Boot ID:                                fdc47560-ee86-48f7-afa6-17da34d85a41
  Kernel Version:                         4.18.0-305.10.2.el8_4.x86_64
  OS Image:                               Red Hat Enterprise Linux CoreOS 48.84.202107202156-0 (Ootpa)
  Operating System:                       linux
  Architecture:                           amd64
  Container Runtime Version:              cri-o://1.21.2-5.rhaos4.8.gitb27d974.el8
  Kubelet Version:                        v1.21.1+051ac4f
  Kube-Proxy Version:                     v1.21.1+051ac4f
ProviderID:                               aws:///us-east-2a/i-03cec6b3ff2e3f45e
Non-terminated Pods:                      (66 in total)
  Namespace                               Name                                                         CPU Requests  CPU Limits   Memory Requests  Memory Limits  AGE
  ---------                               ----                                                         ------------  ----------   ---------------  -------------  ---
  hive                                    hiveadmission-84c8d874dd-bmmkg                               0 (0%)        0 (0%)       0 (0%)           0 (0%)         31m
  open-cluster-management-agent-addon     klusterlet-addon-iampolicyctrl-5b98c98f4c-r2lnd              0 (0%)        0 (0%)       150Mi (0%)       300Mi (0%)     18h
  open-cluster-management-agent-addon     klusterlet-addon-operator-947694b8b-qrpkk                    0 (0%)        0 (0%)       0 (0%)           0 (0%)         18h
  open-cluster-management-agent-addon     klusterlet-addon-policyctrl-config-policy-9ff5dc88b-cbhqp    0 (0%)        0 (0%)       128Mi (0%)       256Mi (0%)     18h
  open-cluster-management-agent-addon     klusterlet-addon-workmgr-fc5d764c-qjkxm                      0 (0%)        0 (0%)       128Mi (0%)       512Mi (1%)     18h
  open-cluster-management-agent           klusterlet-registration-agent-784bc4656b-4n2pv               100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-agent           klusterlet-work-agent-79cddbb5d8-phfq9                       100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-agent           klusterlet-work-agent-79cddbb5d8-s6smz                       100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-placement-controller-697486d48b-ngrcc        100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-placement-controller-697486d48b-nwd49        100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-registration-controller-6484b67847-gnkm6     100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-registration-webhook-5fc7bf6fb9-d6ksm        100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-registration-webhook-5fc7bf6fb9-k9drp        100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management-hub             cluster-manager-work-webhook-5d589b75dd-dtmpr                100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management                 application-chart-c3d40-applicationui-6d47bd8cb8-hvjnl       50m (0%)      0 (0%)       256Mi (0%)       0 (0%)         18h
  open-cluster-management                 application-chart-c3d40-consoleapi-5dc7cf68f9-7msl5          5m (0%)       0 (0%)       80Mi (0%)        512Mi (1%)     18h
  open-cluster-management                 cluster-curator-controller-58459d6c55-ctgpx                  3m (0%)       10m (0%)     25Mi (0%)        128Mi (0%)     18h
  open-cluster-management                 cluster-manager-7fbc796484-kb5hg                             100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management                 cluster-manager-7fbc796484-v4f6q                             100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  open-cluster-management                 clusterlifecycle-state-metrics-v2-7d89d4b68c-vxjt5           25m (0%)      500m (6%)    32Mi (0%)        256Mi (0%)     18h
  open-cluster-management                 console-chart-26608-console-v2-5d569dd5cc-67c52              3m (0%)       0 (0%)       40Mi (0%)        0 (0%)         18h
  open-cluster-management                 discovery-operator-694fcfdfc5-pztv4                          100m (1%)     300m (4%)    100Mi (0%)       500Mi (1%)     18h
  open-cluster-management                 grc-9959f-grcui-5cf85d6d7c-jc8zb                             100m (1%)     0 (0%)       256Mi (0%)       0 (0%)         18h
  open-cluster-management                 grc-9959f-grcuiapi-79cd9dddd9-jnbvj                          50m (0%)      0 (0%)       256Mi (0%)       0 (0%)         18h
  open-cluster-management                 grc-9959f-policy-propagator-59b94c5b8f-pj6ns                 25m (0%)      0 (0%)       64Mi (0%)        0 (0%)         18h
  open-cluster-management                 klusterlet-addon-controller-v2-5cf7c95865-bqr7v              50m (0%)      500m (6%)    96Mi (0%)        2Gi (6%)       18h
  open-cluster-management                 managedcluster-import-controller-v2-59f5f997f7-b72wh         50m (0%)      500m (6%)    96Mi (0%)        2Gi (6%)       18h
  open-cluster-management                 management-ingress-3ef43-547bbd5698-sz42z                    200m (2%)     0 (0%)       256Mi (0%)       0 (0%)         18h
  open-cluster-management                 multicluster-operators-application-766dd9c698-wb74j          300m (4%)     1450m (19%)  256Mi (0%)       2Gi (6%)       18h
  open-cluster-management                 multicluster-operators-hub-subscription-79556bc958-v88j5     150m (2%)     750m (10%)   128Mi (0%)       2Gi (6%)       18h
  open-cluster-management                 ocm-controller-6cd994fcbf-f64b8                              100m (1%)     0 (0%)       256Mi (0%)       2Gi (6%)       18h
  open-cluster-management                 ocm-proxyserver-6bd94d6668-g9m8k                             100m (1%)     0 (0%)       256Mi (0%)       2Gi (6%)       18h
  open-cluster-management                 ocm-webhook-866b658f4c-mw95l                                 50m (0%)      0 (0%)       128Mi (0%)       256Mi (0%)     18h
  open-cluster-management                 policyreport-c310a-insights-client-cbf4ccc59-24hcr           25m (0%)      0 (0%)       32Mi (0%)        512Mi (1%)     18h
  open-cluster-management                 policyreport-c310a-metrics-78bb67d69f-hr7cc                  25m (0%)      0 (0%)       32Mi (0%)        512Mi (1%)     18h
  open-cluster-management                 search-prod-798ef-search-api-69d6b57db4-9ch5h                25m (0%)      0 (0%)       128Mi (0%)       1Gi (3%)       18h
  open-cluster-management                 search-prod-798ef-search-collector-659bb7c497-jwm8z          25m (0%)      0 (0%)       64Mi (0%)        768Mi (2%)     18h
  open-cluster-management                 search-ui-66684dbcb7-nvcrh                                   10m (0%)      0 (0%)       96Mi (0%)        256Mi (0%)     18h
  open-cluster-management                 submariner-addon-55d5dc894d-xxrhf                            100m (1%)     0 (0%)       128Mi (0%)       0 (0%)         18h
  openshift-cluster-csi-drivers           aws-ebs-csi-driver-node-jd72w                                30m (0%)      0 (0%)       150Mi (0%)       0 (0%)         19h
  openshift-cluster-node-tuning-operator  tuned-gqvmd                                                  10m (0%)      0 (0%)       50Mi (0%)        0 (0%)         19h
  openshift-dns                           dns-default-dtgqv                                            60m (0%)      0 (0%)       110Mi (0%)       0 (0%)         19h
  openshift-dns                           node-resolver-s68dn                                          5m (0%)       0 (0%)       21Mi (0%)        0 (0%)         19h
  openshift-image-registry                image-registry-78f745747f-dxw48                              100m (1%)     0 (0%)       256Mi (0%)       0 (0%)         19h
  openshift-image-registry                node-ca-q8hf6                                                10m (0%)      0 (0%)       10Mi (0%)        0 (0%)         19h
  openshift-ingress-canary                ingress-canary-qcw4l                                         10m (0%)      0 (0%)       20Mi (0%)        0 (0%)         19h
  openshift-ingress                       router-default-9b5c98c79-dxrmv                               100m (1%)     0 (0%)       256Mi (0%)       0 (0%)         19h
  openshift-machine-config-operator       machine-config-daemon-fcccd                                  40m (0%)      0 (0%)       100Mi (0%)       0 (0%)         19h
  openshift-marketplace                   certified-operators-jvpnt                                    10m (0%)      0 (0%)       50Mi (0%)        0 (0%)         143m
  openshift-marketplace                   community-operators-v98hl                                    10m (0%)      0 (0%)       50Mi (0%)        0 (0%)         66m
  openshift-marketplace                   redhat-marketplace-pp8c8                                     10m (0%)      0 (0%)       50Mi (0%)        0 (0%)         19h
  openshift-marketplace                   redhat-operators-6xlcb                                       10m (0%)      0 (0%)       50Mi (0%)        0 (0%)         15m
  openshift-monitoring                    alertmanager-main-1                                          8m (0%)       0 (0%)       105Mi (0%)       0 (0%)         19h
  openshift-monitoring                    kube-state-metrics-5f457b6bc7-w92q8                          4m (0%)       0 (0%)       110Mi (0%)       0 (0%)         19h
  openshift-monitoring                    node-exporter-wkx8l                                          9m (0%)       0 (0%)       47Mi (0%)        0 (0%)         19h
  openshift-monitoring                    openshift-state-metrics-67cb99cb76-shwjw                     3m (0%)       0 (0%)       72Mi (0%)        0 (0%)         19h
  openshift-monitoring                    prometheus-adapter-594747b696-rtqnv                          1m (0%)       0 (0%)       40Mi (0%)        0 (0%)         28m
  openshift-monitoring                    prometheus-k8s-1                                             76m (1%)      0 (0%)       1119Mi (3%)      0 (0%)         19h
  openshift-monitoring                    telemeter-client-564c5f8bbd-frz66                            3m (0%)       0 (0%)       70Mi (0%)        0 (0%)         19h
  openshift-monitoring                    thanos-querier-5c7b8b8c8f-8znpg                              14m (0%)      0 (0%)       77Mi (0%)        0 (0%)         19h
  openshift-multus                        multus-additional-cni-plugins-lxnkg                          10m (0%)      0 (0%)       10Mi (0%)        0 (0%)         19h
  openshift-multus                        multus-w9mxn                                                 10m (0%)      0 (0%)       65Mi (0%)        0 (0%)         19h
  openshift-multus                        network-metrics-daemon-9ck4p                                 20m (0%)      0 (0%)       120Mi (0%)       0 (0%)         19h
  openshift-network-diagnostics           network-check-source-55555c9df6-p976s                        10m (0%)      0 (0%)       40Mi (0%)        0 (0%)         19h
  openshift-network-diagnostics           network-check-target-72zzt                                   10m (0%)      0 (0%)       15Mi (0%)        0 (0%)         19h
  openshift-sdn                           sdn-nrwkx                                                    110m (1%)     0 (0%)       220Mi (0%)       0 (0%)         19h
Allocated resources:
  (Total limits may be over 100 percent, i.e., overcommitted.)
  Resource                    Requests      Limits
  --------                    --------      ------
  cpu                         3364m (44%)   4010m (53%)
  memory                      8158Mi (26%)  18080Mi (59%)
  ephemeral-storage           0 (0%)        0 (0%)
  hugepages-1Gi               0 (0%)        0 (0%)
  hugepages-2Mi               0 (0%)        0 (0%)
  attachable-volumes-aws-ebs  0             0
Events:                       <none>
rgupta@rgupta-mac frontend % oc get pod --all-namespaces -o wide
NAMESPACE                                          NAME                                                                  READY   STATUS      RESTARTS   AGE     IP             NODE                                         NOMINATED NODE   READINESS GATES
austin                                             austin-0-6whds-provision-vb8d5                                        0/3     Completed   0          18h     10.131.0.62    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
hive                                               hive-clustersync-0                                                    1/1     Running     0          18h     10.131.0.26    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
hive                                               hive-controllers-77c45f8867-kllgp                                     1/1     Running     0          18h     10.131.0.28    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
hive                                               hiveadmission-84c8d874dd-bmmkg                                        1/1     Running     0          31m     10.128.3.197   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
hive                                               hiveadmission-84c8d874dd-wzvdz                                        1/1     Running     0          31m     10.131.0.64    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-appmgr-79f7d97bf4-trtfg                              1/1     Running     1          18h     10.131.0.59    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-certpolicyctrl-f6f7fd8c8-fp8xp                       1/1     Running     0          18h     10.131.0.60    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-iampolicyctrl-5b98c98f4c-r2lnd                       1/1     Running     0          18h     10.128.2.68    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-operator-947694b8b-qrpkk                             1/1     Running     0          18h     10.128.2.67    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-policyctrl-config-policy-9ff5dc88b-cbhqp             1/1     Running     0          18h     10.128.2.69    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-policyctrl-framework-5bcf996b96-fhdqc                2/2     Running     0          18h     10.131.0.61    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent-addon                klusterlet-addon-workmgr-fc5d764c-qjkxm                               1/1     Running     0          18h     10.128.2.70    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-bdcd45dd-j4zr2                                             1/1     Running     0          18h     10.131.0.55    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-registration-agent-784bc4656b-4n2pv                        1/1     Running     0          18h     10.128.2.66    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-registration-agent-784bc4656b-jv4tp                        1/1     Running     0          18h     10.131.0.57    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-registration-agent-784bc4656b-z7vrz                        1/1     Running     0          18h     10.131.0.56    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-work-agent-79cddbb5d8-ng5pm                                1/1     Running     0          18h     10.131.0.58    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-work-agent-79cddbb5d8-phfq9                                1/1     Running     1          18h     10.128.2.64    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-agent                      klusterlet-work-agent-79cddbb5d8-s6smz                                1/1     Running     0          18h     10.128.2.65    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-placement-controller-697486d48b-ngrcc                 1/1     Running     0          18h     10.128.2.45    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-placement-controller-697486d48b-nwd49                 1/1     Running     0          18h     10.128.2.46    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-placement-controller-697486d48b-w8szb                 1/1     Running     0          18h     10.131.0.36    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-controller-6484b67847-gnkm6              1/1     Running     0          18h     10.128.2.39    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-controller-6484b67847-gz9zw              1/1     Running     0          18h     10.131.0.32    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-controller-6484b67847-tzv6v              1/1     Running     0          18h     10.131.0.33    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-webhook-5fc7bf6fb9-d6ksm                 1/1     Running     0          18h     10.128.2.42    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-webhook-5fc7bf6fb9-j8g5g                 1/1     Running     0          18h     10.131.0.35    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-registration-webhook-5fc7bf6fb9-k9drp                 1/1     Running     0          18h     10.128.2.40    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-work-webhook-5d589b75dd-dtmpr                         1/1     Running     0          18h     10.128.2.43    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-work-webhook-5d589b75dd-q2tcn                         1/1     Running     0          18h     10.131.0.38    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management-hub                        cluster-manager-work-webhook-5d589b75dd-rf2s9                         1/1     Running     0          18h     10.131.0.37    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            application-chart-c3d40-applicationui-6d47bd8cb8-95cr8                1/1     Running     0          18h     10.131.0.30    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            application-chart-c3d40-applicationui-6d47bd8cb8-hvjnl                1/1     Running     0          18h     10.128.2.37    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            application-chart-c3d40-consoleapi-5dc7cf68f9-7msl5                   1/1     Running     0          18h     10.128.2.38    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            application-chart-c3d40-consoleapi-5dc7cf68f9-cnpw6                   1/1     Running     0          18h     10.131.0.31    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            cluster-curator-controller-58459d6c55-6ccn6                           1/1     Running     0          18h     10.131.0.44    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            cluster-curator-controller-58459d6c55-ctgpx                           1/1     Running     0          18h     10.128.2.52    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            cluster-manager-7fbc796484-9hv6z                                      1/1     Running     0          18h     10.131.0.23    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            cluster-manager-7fbc796484-kb5hg                                      1/1     Running     0          18h     10.128.2.29    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            cluster-manager-7fbc796484-v4f6q                                      1/1     Running     0          18h     10.128.2.28    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            clusterlifecycle-state-metrics-v2-7d89d4b68c-vxjt5                    1/1     Running     0          18h     10.128.2.57    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            console-chart-26608-console-v2-5d569dd5cc-67c52                       1/1     Running     0          18h     10.128.2.58    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            console-chart-26608-console-v2-5d569dd5cc-bmhdq                       1/1     Running     0          18h     10.131.0.50    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            discovery-operator-694fcfdfc5-pztv4                                   1/1     Running     1          18h     10.128.2.44    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            fc4572fac125b25a5204980595f40104d03ce1705a6bd5297669e3e247cvtnx       0/1     Completed   0          19h     10.131.0.17    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-grcui-5cf85d6d7c-9qgvg                                      1/1     Running     0          18h     10.131.0.40    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-grcui-5cf85d6d7c-jc8zb                                      1/1     Running     0          18h     10.128.2.48    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-grcuiapi-79cd9dddd9-jnbvj                                   1/1     Running     0          18h     10.128.2.54    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-grcuiapi-79cd9dddd9-m4d7r                                   1/1     Running     0          18h     10.131.0.47    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-policy-propagator-59b94c5b8f-bsvbf                          1/1     Running     0          18h     10.131.0.41    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            grc-9959f-policy-propagator-59b94c5b8f-pj6ns                          1/1     Running     0          18h     10.128.2.47    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            hive-operator-646dd7c89f-nr2ns                                        1/1     Running     0          18h     10.131.0.18    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            infrastructure-operator-647bd65474-7vmp7                              1/1     Running     1          18h     10.131.0.39    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            klusterlet-addon-controller-v2-5cf7c95865-bqr7v                       1/1     Running     1          18h     10.128.2.50    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            klusterlet-addon-controller-v2-5cf7c95865-vv2x5                       1/1     Running     0          18h     10.131.0.45    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            kui-web-terminal-89859bd4f-vzptf                                      1/1     Running     0          18h     10.131.0.51    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            managedcluster-import-controller-v2-59f5f997f7-b72wh                  1/1     Running     0          18h     10.128.2.51    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            managedcluster-import-controller-v2-59f5f997f7-kfdlh                  1/1     Running     0          18h     10.131.0.43    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            management-ingress-3ef43-547bbd5698-f7z5t                             2/2     Running     0          18h     10.131.0.52    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            management-ingress-3ef43-547bbd5698-sz42z                             2/2     Running     0          18h     10.128.2.59    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multicluster-observability-operator-5bc7874494-6g5g2                  1/1     Running     0          18h     10.131.0.19    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multicluster-operators-application-766dd9c698-wb74j                   4/4     Running     3          18h     10.128.2.31    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multicluster-operators-channel-b86bc9965-cxwns                        1/1     Running     2          18h     10.131.0.21    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multicluster-operators-hub-subscription-79556bc958-v88j5              1/1     Running     0          18h     10.128.2.27    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multicluster-operators-standalone-subscription-6fd866c769-5wtls       1/1     Running     0          18h     10.131.0.22    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multiclusterhub-operator-64f9f9f6f-c89zp                              1/1     Running     0          18h     10.131.0.20    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            multiclusterhub-repo-75665bb655-lgwtg                                 1/1     Running     0          18h     10.131.0.24    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-controller-6cd994fcbf-984bq                                       1/1     Running     0          18h     10.131.0.29    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-controller-6cd994fcbf-f64b8                                       1/1     Running     0          18h     10.128.2.36    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-proxyserver-6bd94d6668-g9m8k                                      1/1     Running     0          18h     10.128.2.41    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-proxyserver-6bd94d6668-r6lx2                                      1/1     Running     0          18h     10.131.0.34    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-webhook-866b658f4c-mw95l                                          1/1     Running     0          18h     10.128.2.34    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            ocm-webhook-866b658f4c-w8djj                                          1/1     Running     0          18h     10.131.0.25    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            policyreport-c310a-insights-client-cbf4ccc59-24hcr                    1/1     Running     0          18h     10.128.2.49    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            policyreport-c310a-metrics-78bb67d69f-hr7cc                           1/1     Running     0          18h     10.128.2.53    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            provider-credential-controller-c4c5b478-9jlhz                         2/2     Running     0          18h     10.131.0.42    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            redhat-operators-snapshot-acm-tccpj                                   1/1     Running     0          19h     10.131.0.16    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-operator-c66cf878b-5xm4x                                       1/1     Running     0          18h     10.131.0.49    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-prod-798ef-search-aggregator-f9558d859-qnspl                   1/1     Running     0          18h     10.131.0.48    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-prod-798ef-search-api-69d6b57db4-9ch5h                         1/1     Running     0          18h     10.128.2.60    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-prod-798ef-search-api-69d6b57db4-l4hrd                         1/1     Running     0          18h     10.131.0.53    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-prod-798ef-search-collector-659bb7c497-jwm8z                   1/1     Running     0          18h     10.128.2.56    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-redisgraph-0                                                   1/1     Running     0          18h     10.131.0.54    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-ui-66684dbcb7-nvcrh                                            1/1     Running     0          18h     10.128.2.55    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            search-ui-66684dbcb7-tq5wv                                            1/1     Running     0          18h     10.131.0.46    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
open-cluster-management                            submariner-addon-55d5dc894d-xxrhf                                     1/1     Running     0          18h     10.128.2.30    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-apiserver-operator                       openshift-apiserver-operator-8554bc7d64-tqhzh                         1/1     Running     1          19h     10.128.0.10    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-apiserver                                apiserver-b7989c569-4wzrg                                             2/2     Running     0          19h     10.129.0.40    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-apiserver                                apiserver-b7989c569-8w8j4                                             2/2     Running     0          19h     10.128.0.42    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-apiserver                                apiserver-b7989c569-pnl8c                                             2/2     Running     0          19h     10.130.0.48    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-authentication-operator                  authentication-operator-7d8f494d4-qt5dt                               1/1     Running     1          19h     10.130.0.8     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-authentication                           oauth-openshift-85cd898c5b-bvrp8                                      1/1     Running     0          18h     10.129.0.51    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-authentication                           oauth-openshift-85cd898c5b-fc7kl                                      1/1     Running     0          18h     10.128.0.67    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-authentication                           oauth-openshift-85cd898c5b-nqvrk                                      1/1     Running     0          19h     10.130.0.55    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cloud-credential-operator                cloud-credential-operator-b48c98977-r2wgv                             2/2     Running     0          19h     10.128.0.23    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cloud-credential-operator                pod-identity-webhook-6d9f99bc7d-tdq9z                                 1/1     Running     0          19h     10.128.0.46    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-controller-5c9d4bcff8-b6s79                        11/11   Running     6          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-controller-5c9d4bcff8-bb2cd                        11/11   Running     1          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-node-7nlhv                                         3/3     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-node-hjnzg                                         3/3     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-node-hv5g9                                         3/3     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-node-jd72w                                         3/3     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-node-x4nwv                                         3/3     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-csi-drivers                      aws-ebs-csi-driver-operator-9fbcddbdd-t26zq                           1/1     Running     0          19h     10.129.0.3     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-machine-approver                 machine-approver-777b945665-xzvw7                                     2/2     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-node-tuning-operator             cluster-node-tuning-operator-64f4956f8c-mr4jl                         1/1     Running     2          19h     10.130.0.19    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-node-tuning-operator             tuned-9q8vg                                                           1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-node-tuning-operator             tuned-gqvmd                                                           1/1     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-cluster-node-tuning-operator             tuned-j8ffn                                                           1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-node-tuning-operator             tuned-nt7mt                                                           1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-node-tuning-operator             tuned-t4ckk                                                           1/1     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-cluster-samples-operator                 cluster-samples-operator-55bdc56579-h87tq                             2/2     Running     0          19h     10.128.0.34    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-storage-operator                 cluster-storage-operator-575bbcfb67-8jhmz                             1/1     Running     1          19h     10.128.0.5     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-storage-operator                 csi-snapshot-controller-6945c9b4db-2sdkt                              1/1     Running     3          19h     10.129.0.5     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-storage-operator                 csi-snapshot-controller-6945c9b4db-4dzqq                              1/1     Running     0          19h     10.128.0.11    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-storage-operator                 csi-snapshot-controller-operator-847b6b5664-4ksnn                     1/1     Running     0          19h     10.130.0.7     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-cluster-storage-operator                 csi-snapshot-webhook-698db78769-c5bzh                                 1/1     Running     0          19h     10.129.0.11    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-cluster-storage-operator                 csi-snapshot-webhook-698db78769-cc2bc                                 1/1     Running     0          19h     10.128.0.16    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-cluster-version                          cluster-version-operator-5cd85996f7-cx522                             1/1     Running     7          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-config-operator                          openshift-config-operator-dcf5fbcd7-hkzjp                             1/1     Running     1          19h     10.130.0.6     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-console-operator                         console-operator-87b7bc6fd-dj56z                                      1/1     Running     0          19h     10.128.0.35    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-console                                  console-78987b7475-6tr6h                                              1/1     Running     0          19h     10.130.0.54    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-console                                  console-78987b7475-xkrcf                                              1/1     Running     0          19h     10.128.0.60    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-console                                  downloads-8545bd57bc-d8t2c                                            1/1     Running     0          19h     10.129.0.27    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-console                                  downloads-8545bd57bc-gdkbg                                            1/1     Running     0          19h     10.130.0.37    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-controller-manager-operator              openshift-controller-manager-operator-58d484fd7-6km9m                 1/1     Running     1          19h     10.128.0.6     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-controller-manager                       controller-manager-2lhjr                                              1/1     Running     0          28m     10.130.0.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-controller-manager                       controller-manager-2xhdf                                              1/1     Running     0          27m     10.128.0.77    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-controller-manager                       controller-manager-4lc9t                                              1/1     Running     0          28m     10.129.0.61    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-dns-operator                             dns-operator-86cf84444f-x9rk5                                         2/2     Running     0          19h     10.130.0.12    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-dns                                      dns-default-b8vkn                                                     2/2     Running     0          19h     10.129.0.9     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      dns-default-dtgqv                                                     2/2     Running     0          19h     10.128.2.5     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      dns-default-ghbgf                                                     2/2     Running     0          19h     10.130.0.14    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-dns                                      dns-default-pg945                                                     2/2     Running     0          19h     10.128.0.17    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      dns-default-znbwx                                                     2/2     Running     0          19h     10.131.0.4     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      node-resolver-9zgt7                                                   1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      node-resolver-c9zbv                                                   1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-dns                                      node-resolver-hsjkb                                                   1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      node-resolver-pnkqx                                                   1/1     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-dns                                      node-resolver-s68dn                                                   1/1     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-etcd-operator                            etcd-operator-779849cbd6-dm2p8                                        1/1     Running     1          19h     10.128.0.4     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     etcd-ip-10-0-136-67.us-east-2.compute.internal                        4/4     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     etcd-ip-10-0-165-219.us-east-2.compute.internal                       4/4     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     etcd-ip-10-0-217-104.us-east-2.compute.internal                       4/4     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     etcd-quorum-guard-b9bc8d4b-m46kh                                      1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     etcd-quorum-guard-b9bc8d4b-rh4kb                                      1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     etcd-quorum-guard-b9bc8d4b-vfg5w                                      1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     installer-2-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.29    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     installer-2-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.23    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     installer-2-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.15    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     installer-3-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.39    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     installer-3-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.31    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     installer-3-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.36    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     revision-pruner-2-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.31    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     revision-pruner-2-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.24    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     revision-pruner-2-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.28    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     revision-pruner-3-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.43    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-etcd                                     revision-pruner-3-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.33    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-etcd                                     revision-pruner-3-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.40    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           cluster-image-registry-operator-5cd7877b4f-sbzld                      1/1     Running     0          19h     10.130.0.11    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-image-registry                           image-pruner-27162720-qtchj                                           0/1     Completed   0          15h     10.131.0.63    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           image-registry-78f745747f-74hwj                                       1/1     Running     0          19h     10.131.0.8     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           image-registry-78f745747f-dxw48                                       1/1     Running     0          19h     10.128.2.9     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           node-ca-2c9sl                                                         1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           node-ca-2mbjt                                                         1/1     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           node-ca-fgqzw                                                         1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-image-registry                           node-ca-q86q9                                                         1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-image-registry                           node-ca-q8hf6                                                         1/1     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-ingress-canary                           ingress-canary-qcw4l                                                  1/1     Running     0          19h     10.128.2.4     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-ingress-canary                           ingress-canary-wnjlj                                                  1/1     Running     0          19h     10.131.0.5     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-ingress-operator                         ingress-operator-86bb7b98db-xfmvm                                     2/2     Running     4          19h     10.130.0.17    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-ingress                                  router-default-9b5c98c79-dxrmv                                        1/1     Running     0          19h     10.128.2.26    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-ingress                                  router-default-9b5c98c79-tz9p4                                        1/1     Running     0          19h     10.131.0.14    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-insights                                 insights-operator-7994fb78fd-dzq2h                                    1/1     Running     1          19h     10.128.0.9     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver-operator                  kube-apiserver-operator-6776b85f47-x24jr                              1/1     Running     1          19h     10.128.0.7     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-10-ip-10-0-136-67.us-east-2.compute.internal                0/1     Completed   0          18h     10.130.0.62    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           installer-10-ip-10-0-165-219.us-east-2.compute.internal               0/1     Completed   0          18h     10.129.0.56    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-10-ip-10-0-217-104.us-east-2.compute.internal               0/1     Completed   0          18h     10.128.0.66    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-11-ip-10-0-136-67.us-east-2.compute.internal                0/1     Completed   0          74m     10.130.0.64    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           installer-11-ip-10-0-165-219.us-east-2.compute.internal               0/1     Completed   0          82m     10.129.0.58    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-11-ip-10-0-217-104.us-east-2.compute.internal               0/1     Completed   0          90m     10.128.0.72    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-12-ip-10-0-217-104.us-east-2.compute.internal               0/1     Completed   0          30m     10.128.0.74    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-13-ip-10-0-136-67.us-east-2.compute.internal                0/1     Completed   0          15m     10.130.0.68    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           installer-13-ip-10-0-165-219.us-east-2.compute.internal               0/1     Completed   0          22m     10.129.0.62    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-13-ip-10-0-217-104.us-east-2.compute.internal               0/1     Completed   0          28m     10.128.0.76    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-5-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.30    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-7-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.39    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-8-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.34    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-9-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.51    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           installer-9-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.38    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           installer-9-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.57    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           kube-apiserver-ip-10-0-136-67.us-east-2.compute.internal              5/5     Running     0          10m     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           kube-apiserver-ip-10-0-165-219.us-east-2.compute.internal             5/5     Running     0          17m     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           kube-apiserver-ip-10-0-217-104.us-east-2.compute.internal             5/5     Running     0          25m     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-10-ip-10-0-136-67.us-east-2.compute.internal          0/1     Completed   0          18h     10.130.0.63    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           revision-pruner-10-ip-10-0-165-219.us-east-2.compute.internal         0/1     Completed   0          18h     10.129.0.57    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-10-ip-10-0-217-104.us-east-2.compute.internal         0/1     Completed   0          18h     10.128.0.71    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-11-ip-10-0-136-67.us-east-2.compute.internal          0/1     Completed   0          66m     10.130.0.65    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           revision-pruner-11-ip-10-0-165-219.us-east-2.compute.internal         0/1     Completed   0          74m     10.129.0.59    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-11-ip-10-0-217-104.us-east-2.compute.internal         0/1     Completed   0          82m     10.128.0.73    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-13-ip-10-0-136-67.us-east-2.compute.internal          0/1     Completed   0          7m24s   10.130.0.69    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           revision-pruner-13-ip-10-0-165-219.us-east-2.compute.internal         0/1     Completed   0          15m     10.129.0.63    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-13-ip-10-0-217-104.us-east-2.compute.internal         0/1     Completed   0          23m     10.128.0.78    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-9-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.52    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-apiserver                           revision-pruner-9-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.46    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-apiserver                           revision-pruner-9-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.58    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager-operator         kube-controller-manager-operator-85fc49fd54-64wjb                     1/1     Running     1          19h     10.130.0.4     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-2-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.20    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-3-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.25    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-3-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.17    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-4-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.25    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-4-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.29    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-5-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.34    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-5-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.26    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-5-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.41    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-6-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.45    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-6-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.36    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-6-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.45    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-7-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.49    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-7-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.42    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-7-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.53    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-8-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          18h     10.130.0.56    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-8-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.48    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-8-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.62    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-9-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          18h     10.130.0.59    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  installer-9-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          18h     10.129.0.53    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  installer-9-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          18h     10.128.0.65    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  kube-controller-manager-ip-10-0-136-67.us-east-2.compute.internal     4/4     Running     2          18h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  kube-controller-manager-ip-10-0-165-219.us-east-2.compute.internal    4/4     Running     1          18h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  kube-controller-manager-ip-10-0-217-104.us-east-2.compute.internal    4/4     Running     2          18h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-3-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.30    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-3-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.22    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-4-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.31    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-5-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.36    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-5-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.28    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-6-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.47    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-6-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.39    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-6-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.50    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-7-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.50    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-7-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.45    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-7-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.54    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-8-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          18h     10.130.0.57    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-8-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          18h     10.129.0.50    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-8-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.63    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-9-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          18h     10.130.0.61    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-controller-manager                  revision-pruner-9-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          18h     10.129.0.55    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-controller-manager                  revision-pruner-9-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          18h     10.128.0.68    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler-operator                  openshift-kube-scheduler-operator-7678b47f-tb85d                      1/1     Running     1          19h     10.130.0.3     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-3-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.13    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-4-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.21    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-5-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.28    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-5-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.32    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-6-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.38    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-6-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.29    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-6-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.33    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-7-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          19h     10.130.0.40    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-7-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          19h     10.129.0.41    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-7-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.51    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-8-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          18h     10.129.0.49    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-8-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          19h     10.128.0.61    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-9-ip-10-0-136-67.us-east-2.compute.internal                 0/1     Completed   0          18h     10.130.0.58    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           installer-9-ip-10-0-165-219.us-east-2.compute.internal                0/1     Completed   0          18h     10.129.0.52    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           installer-9-ip-10-0-217-104.us-east-2.compute.internal                0/1     Completed   0          18h     10.128.0.69    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           openshift-kube-scheduler-ip-10-0-136-67.us-east-2.compute.internal    3/3     Running     2          18h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           openshift-kube-scheduler-ip-10-0-165-219.us-east-2.compute.internal   3/3     Running     3          18h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           openshift-kube-scheduler-ip-10-0-217-104.us-east-2.compute.internal   3/3     Running     1          18h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-5-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.33    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           revision-pruner-6-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.32    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-6-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.38    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-7-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          19h     10.130.0.44    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           revision-pruner-7-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          19h     10.129.0.44    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-7-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          19h     10.128.0.52    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-8-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          18h     10.128.0.64    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-9-ip-10-0-136-67.us-east-2.compute.internal           0/1     Completed   0          18h     10.130.0.60    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-scheduler                           revision-pruner-9-ip-10-0-165-219.us-east-2.compute.internal          0/1     Completed   0          18h     10.129.0.54    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-kube-scheduler                           revision-pruner-9-ip-10-0-217-104.us-east-2.compute.internal          0/1     Completed   0          18h     10.128.0.70    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-kube-storage-version-migrator-operator   kube-storage-version-migrator-operator-785dd9f8-7gwqh                 1/1     Running     1          19h     10.130.0.9     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-kube-storage-version-migrator            migrator-6f9d44d9c8-rkcgm                                             1/1     Running     0          19h     10.129.0.4     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-machine-api                              cluster-autoscaler-operator-9c5f6b9d7-9g5x5                           2/2     Running     0          19h     10.130.0.16    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-machine-api                              cluster-baremetal-operator-67556fbc86-56kdd                           2/2     Running     0          19h     10.128.0.21    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-machine-api                              machine-api-controllers-77fcd7f755-2hqp2                              7/7     Running     0          19h     10.129.0.15    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-machine-api                              machine-api-operator-64df6bd767-c6rnv                                 2/2     Running     0          19h     10.130.0.20    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-machine-config-operator                  machine-config-controller-67d9cd779b-gscz7                            1/1     Running     0          19h     10.129.0.12    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-daemon-bxbrg                                           2/2     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-daemon-fcccd                                           2/2     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-daemon-hhtj7                                           2/2     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-machine-config-operator                  machine-config-daemon-trdjq                                           2/2     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-daemon-wj28l                                           2/2     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-operator-5d4cb78d88-8ftc7                              1/1     Running     0          19h     10.128.0.8     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-server-8wczw                                           1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-machine-config-operator                  machine-config-server-ccjc7                                           1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-machine-config-operator                  machine-config-server-dtgxl                                           1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-marketplace                              certified-operators-jvpnt                                             1/1     Running     0          144m    10.128.3.157   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-marketplace                              community-operators-v98hl                                             1/1     Running     0          66m     10.128.3.184   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-marketplace                              marketplace-operator-744b969b6-s9dgt                                  1/1     Running     0          19h     10.128.0.12    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-marketplace                              redhat-marketplace-pp8c8                                              1/1     Running     0          19h     10.128.2.14    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-marketplace                              redhat-operators-6xlcb                                                1/1     Running     0          15m     10.128.3.205   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               alertmanager-main-0                                                   5/5     Running     0          19h     10.131.0.9     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               alertmanager-main-1                                                   5/5     Running     0          19h     10.128.2.17    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               alertmanager-main-2                                                   5/5     Running     0          19h     10.131.0.10    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               cluster-monitoring-operator-75f69c8797-268fn                          2/2     Running     3          19h     10.130.0.5     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-monitoring                               grafana-6d68f8478f-5wxhj                                              2/2     Running     0          19h     10.131.0.11    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               kube-state-metrics-5f457b6bc7-w92q8                                   3/3     Running     0          19h     10.128.2.8     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               node-exporter-7tg4f                                                   2/2     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               node-exporter-hsvms                                                   2/2     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               node-exporter-kvb88                                                   2/2     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-monitoring                               node-exporter-nzzvt                                                   2/2     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               node-exporter-wkx8l                                                   2/2     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               openshift-state-metrics-67cb99cb76-shwjw                              3/3     Running     0          19h     10.128.2.7     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               prometheus-adapter-594747b696-npgzl                                   1/1     Running     0          28m     10.131.0.66    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               prometheus-adapter-594747b696-rtqnv                                   1/1     Running     0          28m     10.128.3.201   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               prometheus-k8s-0                                                      7/7     Running     1          19h     10.131.0.13    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               prometheus-k8s-1                                                      7/7     Running     1          19h     10.128.2.19    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               prometheus-operator-974874c6d-8h4k6                                   2/2     Running     1          19h     10.129.0.10    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               telemeter-client-564c5f8bbd-frz66                                     3/3     Running     0          19h     10.128.2.6     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               thanos-querier-5c7b8b8c8f-8znpg                                       5/5     Running     0          19h     10.128.2.18    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-monitoring                               thanos-querier-5c7b8b8c8f-hh58f                                       5/5     Running     0          19h     10.131.0.12    ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-6x54t                                                          1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-additional-cni-plugins-2szr9                                   1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-multus                                   multus-additional-cni-plugins-7zbq5                                   1/1     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-additional-cni-plugins-ktzwz                                   1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-additional-cni-plugins-lxnkg                                   1/1     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-additional-cni-plugins-m4pmv                                   1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-admission-controller-7z4vl                                     2/2     Running     0          19h     10.130.0.10    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-multus                                   multus-admission-controller-jndl5                                     2/2     Running     0          19h     10.129.0.8     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-admission-controller-phkwx                                     2/2     Running     0          19h     10.128.0.19    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-bv9ll                                                          1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-multus                                   multus-gjdnv                                                          1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-hznlr                                                          1/1     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   multus-w9mxn                                                          1/1     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   network-metrics-daemon-5qwv8                                          2/2     Running     0          19h     10.129.0.7     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   network-metrics-daemon-9ck4p                                          2/2     Running     0          19h     10.128.2.3     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   network-metrics-daemon-dq9hx                                          2/2     Running     0          19h     10.131.0.2     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   network-metrics-daemon-n5786                                          2/2     Running     0          19h     10.128.0.13    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-multus                                   network-metrics-daemon-vqwmm                                          2/2     Running     0          19h     10.130.0.13    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-network-diagnostics                      network-check-source-55555c9df6-p976s                                 1/1     Running     0          19h     10.128.2.13    ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-network-diagnostics                      network-check-target-72zzt                                            1/1     Running     0          19h     10.128.2.2     ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-network-diagnostics                      network-check-target-856gd                                            1/1     Running     0          19h     10.131.0.3     ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-network-diagnostics                      network-check-target-98nl9                                            1/1     Running     0          19h     10.129.0.2     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-network-diagnostics                      network-check-target-pq7cc                                            1/1     Running     0          19h     10.130.0.2     ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-network-diagnostics                      network-check-target-rwcc8                                            1/1     Running     0          19h     10.128.0.2     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-network-operator                         network-operator-56c9d7d8c4-k27d6                                     1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-oauth-apiserver                          apiserver-9d596bf56-5hklh                                             1/1     Running     0          19h     10.129.0.18    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-oauth-apiserver                          apiserver-9d596bf56-9vjrx                                             1/1     Running     0          19h     10.130.0.23    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-oauth-apiserver                          apiserver-9d596bf56-tzz86                                             1/1     Running     0          19h     10.128.0.25    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-operator-lifecycle-manager               catalog-operator-75dd6d7c9-t27nj                                      1/1     Running     0          19h     10.130.0.18    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-operator-lifecycle-manager               olm-operator-84ccfcf594-4v24k                                         1/1     Running     0          19h     10.128.0.22    ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-operator-lifecycle-manager               packageserver-796bb59574-8vpwg                                        1/1     Running     0          19h     10.130.0.22    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-operator-lifecycle-manager               packageserver-796bb59574-krg76                                        1/1     Running     0          19h     10.129.0.16    ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-4khjf                                                             2/2     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-controller-ctzmn                                                  1/1     Running     0          19h     10.0.217.104   ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-controller-fw5kz                                                  1/1     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-sdn                                      sdn-controller-t4rj9                                                  1/1     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-gvmd2                                                             2/2     Running     0          19h     10.0.165.219   ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-nrwkx                                                             2/2     Running     0          19h     10.0.153.232   ip-10-0-153-232.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-q5lq9                                                             2/2     Running     0          19h     10.0.164.238   ip-10-0-164-238.us-east-2.compute.internal   <none>           <none>
openshift-sdn                                      sdn-vs5nq                                                             2/2     Running     0          19h     10.0.136.67    ip-10-0-136-67.us-east-2.compute.internal    <none>           <none>
openshift-service-ca-operator                      service-ca-operator-766694895b-qswwx                                  1/1     Running     1          19h     10.128.0.3     ip-10-0-217-104.us-east-2.compute.internal   <none>           <none>
openshift-service-ca                               service-ca-7d8d496945-h5tk4                                           1/1     Running     0          19h     10.129.0.6     ip-10-0-165-219.us-east-2.compute.internal   <none>           <none>
rgupta@rgupta-mac frontend % crc status
CRC VM:          Stopped
OpenShift:       Stopped (v4.7.18)
Disk Usage:      0B of 0B (Inside the CRC VM)
Cache Usage:     11.05GB
Cache Directory: /Users/rgupta/.crc/cache
rgupta@rgupta-mac frontend % crc start
  [Restored Jun 23, 2023 at 8:46:16 AM]
Last login: Fri Jun 23 08:46:13 on console
rgupta@rgupta-mac frontend % 
  [Restored Jun 26, 2023 at 8:08:10 AM]
Last login: Mon Jun 26 08:08:07 on console
rgupta@rgupta-mac frontend % 
  [Restored Jun 28, 2023 at 8:33:59 AM]
Last login: Wed Jun 28 08:30:59 on console
rgupta@rgupta-mac frontend % sdsfdargoPass=$(oc get secret/openshift-gitops-cluster -n openshift-gitops -o jsonpath='{.data.admin\.password}' | base64 -d)
echo $argoPass
Unable to connect to the server: dial tcp: lookup api.cluster-t68tn.t68tn.sandbox977.opentlc.com on 192.168.86.1:53: no such host

rgupta@rgupta-mac frontend % oc login https://api.cluster-4xczl.4xczl.sandbox500.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-4xczl.4xczl.sandbox500.opentlc.com/oauth/token/request
rgupta@rgupta-mac frontend % oc login --token=sha256~WDVBuj9mn5BoyWA_HA1TplDMiULO8s6buHiACbkjZoU --server=https://api.cluster-4xczl.4xczl.sandbox500.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-4xczl.4xczl.sandbox500.opentlc.com:6443" as "admin" using the token provided.

You have access to 87 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac frontend % sdsfdargoPass=$(oc get secret/openshift-gitops-cluster -n openshift-gitops -o jsonpath='{.data.admin\.password}' | base64 -d)           
echo $argoPass
^Z^Z^Z
^C
rgupta@rgupta-mac frontend % 
rgupta@rgupta-mac frontend % 
rgupta@rgupta-mac frontend % argoPass=$(oc get secret/openshift-gitops-cluster -n openshift-gitops -o jsonpath='{.data.admin\.password}' | base64 -d)
echo $argoPass
PtMnF8ucqJpf2iv1hbmyDAGj6IrsTR9Q
rgupta@rgupta-mac frontend % kubectl apply -f documentation/modules/ROOT/examples/bgd-app/bgd-app.yaml
error: the path "documentation/modules/ROOT/examples/bgd-app/bgd-app.yaml" does not exist
rgupta@rgupta-mac frontend % git clone https://github.com/redhat-developer-demos/openshift-gitops-examples.git
Cloning into 'openshift-gitops-examples'...
remote: Enumerating objects: 408, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 408 (delta 0), reused 7 (delta 0), pack-reused 400
Receiving objects: 100% (408/408), 61.20 KiB | 1.36 MiB/s, done.
Resolving deltas: 100% (118/118), done.
rgupta@rgupta-mac frontend % ls
Dockerfile			app.js				index.html			node_modules			openshift-gitops-examples	package-lock.json		package.json
rgupta@rgupta-mac frontend % find . -name *.yaml
zsh: no matches found: *.yaml
rgupta@rgupta-mac frontend % cd openshift-gitops-examples 
rgupta@rgupta-mac openshift-gitops-examples % ls
README.md	apps		bootstrap	components
rgupta@rgupta-mac openshift-gitops-examples % find . -name bgd-namespace.yaml
rgupta@rgupta-mac openshift-gitops-examples % pwd
/Users/rgupta/Documents/keycloak/Keycloak-Identity-and-Access-Management-for-Modern-Applications/ch2/frontend/openshift-gitops-examples
rgupta@rgupta-mac openshift-gitops-examples % cd ..
rgupta@rgupta-mac frontend % bgd-namespace.yaml
zsh: command not found: bgd-namespace.yaml
rgupta@rgupta-mac frontend % ls
Dockerfile			app.js				index.html			node_modules			openshift-gitops-examples	package-lock.json		package.json
rgupta@rgupta-mac frontend % vi bgd-namespace.yaml
rgupta@rgupta-mac frontend % kubectl apply -f bgd-namespace.yaml 
namespace/bgd created
rgupta@rgupta-mac frontend % vi bgd-d.yaml
rgupta@rgupta-mac frontend % kubectl apply -f bgd-d.yaml 
deployment.apps/bgd created
rgupta@rgupta-mac frontend % ls
Dockerfile			bgd-d.yaml			index.html			openshift-gitops-examples	package.json
app.js				bgd-namespace.yaml		node_modules			package-lock.json
rgupta@rgupta-mac frontend % bi bs.yaml
zsh: command not found: bi
rgupta@rgupta-mac frontend % vi bs.yaml
rgupta@rgupta-mac frontend % kubectl apply -f bs.yaml   
service/bgd created
rgupta@rgupta-mac frontend % vi bg-r.yaml
rgupta@rgupta-mac frontend % kubectl apply -f bg
error: the path "bg" does not exist
rgupta@rgupta-mac frontend % kubectl apply -f bg-r.yaml 
route.route.openshift.io/bgd created
rgupta@rgupta-mac frontend % vi a.yaml
rgupta@rgupta-mac frontend % kubectl apply -f a.yaml 
route.route.openshift.io/bgd unchanged
rgupta@rgupta-mac frontend % pwd
/Users/rgupta/Documents/keycloak/Keycloak-Identity-and-Access-Management-for-Modern-Applications/ch2/frontend
rgupta@rgupta-mac frontend % cd ..
rgupta@rgupta-mac ch2 % cd ..
rgupta@rgupta-mac Keycloak-Identity-and-Access-Management-for-Modern-Applications % ls
LICENSE		README.md	ch13		ch2		ch4		ch5		ch6		ch7		ch9
rgupta@rgupta-mac Keycloak-Identity-and-Access-Management-for-Modern-Applications % pwd
/Users/rgupta/Documents/keycloak/Keycloak-Identity-and-Access-Management-for-Modern-Applications
rgupta@rgupta-mac Keycloak-Identity-and-Access-Management-for-Modern-Applications % cd ..
rgupta@rgupta-mac keycloak % ls
20210808_073729.jpeg						Keycloak-Identity-and-Access-Management-for-Modern-Applications	keycloak-15.0.1.zip
20210809_094102.jpeg						Loan Estimate Package.pdf
Application Package.pdf						keycloak-15.0.1
rgupta@rgupta-mac keycloak % cd ..
rgupta@rgupta-mac Documents % ls
L-What's%20New%20in%20OpenShift%20Container%20Platform%204.7.pptx_0.odp	expenses								personal
WebEx									keycloak								principal
accounts								openshift
rgupta@rgupta-mac Documents % mkdir mcclane
rgupta@rgupta-mac Documents % cd mcclane 
rgupta@rgupta-mac mcclane % git clone https://github.com/rgupta1234/openshift-cicd-demo-1.git
Cloning into 'openshift-cicd-demo-1'...
remote: Enumerating objects: 319, done.
remote: Counting objects: 100% (138/138), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 319 (delta 108), reused 106 (delta 97), pack-reused 181
Receiving objects: 100% (319/319), 1.44 MiB | 4.36 MiB/s, done.
Resolving deltas: 100% (178/178), done.
rgupta@rgupta-mac mcclane % ls
openshift-cicd-demo-1
rgupta@rgupta-mac mcclane % cd *
rgupta@rgupta-mac openshift-cicd-demo-1 % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo-1 % oc login  https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo-1 % oc login --token=sha256~eOJmlMKcD9byKrNSVXUJNmkB3qd8oNDIBZf0HYPH5N8 --server=https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443" as "admin" using the token provided.

You have access to 69 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac openshift-cicd-demo-1 % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo-1 % oc new-project demo
Now using project "demo" on server "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo-1 % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo-1 % demo.sh install
zsh: command not found: demo.sh
rgupta@rgupta-mac openshift-cicd-demo-1 % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo-1 % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   2m52s
NAME       STATUS   AGE
demo-dev   Active   2m53s
NAME         STATUS   AGE
demo-stage   Active   2m52s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
demo.sh install
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-wsd9q created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.yhAvoQOh ~/Documents/mcclane/openshift-cicd-demo-1
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 5.71 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo 83d9a49] Updated manifests git url
 1 file changed, 3 insertions(+), 3 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 456 bytes | 456.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/gitea/spring-petclinic
   aacbbb4..83d9a49  cicd-demo -> cicd-demo
~/Documents/mcclane/openshift-cicd-demo-1

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-f79bv.f79bv.sandbox371.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-f79bv.f79bv.sandbox371.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo-1 % demo.sh install
zsh: command not found: demo.sh
rgupta@rgupta-mac openshift-cicd-demo-1 % opc pac logs -n demo-cicd
zsh: command not found: opc
rgupta@rgupta-mac openshift-cicd-demo-1 % brew install tektoncd-cli
📋
Updating Homebrew...
==> Downloading https://ghcr.io/v2/homebrew/portable-ruby/portable-ruby/blobs/sha256:61029cec31c68a1fae1fa90fa876adf43d0becff777da793f9b5c5577f00567a
##################################################################################################################################################################################################################################################### 100.0%
==> Pouring portable-ruby-2.6.10_1.el_capitan.bottle.tar.gz
==> Auto-updated Homebrew!
Updated 1 tap (homebrew/cask).
==> New Casks
115                                                            elgato-stream-deck                                             mediainfoex                                                    scoot
1kc-razer                                                      elgato-video-capture                                           medis                                                          score
86box                                                          elgato-wave-link                                               mega                                                           scroll
abbyy-finereader-pdf                                           elk                                                            megazeux                                                       scrolla
accord                                                         eloquent                                                       mellel                                                         sdm
active-trader-pro                                              emmetapp                                                       menubarx                                                       segger-jlink
actual                                                         engine-dj                                                      mfiles                                                         semeru-jdk-open
adguard-vpn                                                    enigma                                                         miaoyan                                                        serene
adze                                                           entry                                                          microsoft-office-businesspro                                   shapr3d
aethersx2                                                      eobcanka                                                       microsoft-onenote                                              shop-different
agi                                                            epilogue-operator                                              midi-router-client                                             shureplus-motiv
akiflow                                                        equinox                                                        mighty-mike                                                    sigmaos
alex313031-thorium                                             eset-cyber-security                                            miln-movie-splitter                                            silicon-labs-vcp-driver
alipay-key-tool                                                espanso                                                        mimestream                                                     simpleclock
aliwangwang                                                    eu                                                             minisim                                                        simplemind
almighty                                                       eusamanager                                                    miniwol                                                        sioyek
alpha                                                          far2l                                                          mints                                                          sitala
amazon-luna                                                    fastmarks                                                      mist                                                           skiff
ankama                                                         ferdium                                                        mixed-in-key-live                                              slab
ankerslicer                                                    fertigt-slate                                                  mixin                                                          slack-cli
ankerwork                                                      fig                                                            mmhmm-studio                                                   smartreporter-free
anypointstudio                                                 fightcade                                                      mochi-diffusion                                                smooze-pro
anytype                                                        filemonitor                                                    moderndeck                                                     smplayer
apifox                                                         filen                                                          moneymanager                                                   sms-plus
apipost                                                        finalshell                                                     monofocus                                                      snapmaker-luban
app-fair                                                       finch                                                          moradownloader                                                 sol
appflowy                                                       firefly-shimmer                                                morgen                                                         sonic-lineup
appium-inspector                                               fishing-funds                                                  motu-m-series                                                  sonic3air
apple-hewlett-packard-printer-drivers                          flacon                                                         mp3tag                                                         sonixd
aptakube                                                       fleet                                                          mullvad-browser                                                sonos
arc                                                            fly-key                                                        multiviewer-for-f1                                             sony-ps-remote-play
archaeology                                                    flycast                                                        mumu-x                                                         soothe2
archy                                                          fmail                                                          mural                                                          soulver-cli
arctype                                                        fmail2                                                         music-miniplayer                                               soundtoys
arduino-ide                                                    focusrite-control                                              music-remote                                                   spaceid
ares                                                           focusrite-saffire-mixcontrol                                   music-widget                                                   spike
asix-ax88179                                                   folder-colorizer                                               mweb-pro                                                       spline
astrofox                                                       forkgram-telegram                                              mx-power-gadget                                                spotify4bigsur
athens                                                         fotokasten                                                     mysteriumvpn                                                   spybuster
attachecase                                                    foxglove-studio                                                nanoem                                                         sqlcl
audiocupcake                                                   foxit-pdf-editor                                               nanosaur                                                       squash
audiorelay                                                     fractal-bot                                                    nanosaur2                                                      ssdreporter-free
avifquicklook                                                  frappe-books                                                   neat                                                           starnet-plus-plus
avtouchbar                                                     free-gpgmail                                                   neovide                                                        steam-plus-plus
bambu-studio                                                   fresh                                                          nimblenote                                                     steelseries-engine
banana-cake-pop                                                fs-uae-launcher                                                nitro-pdf-pro                                                  steelseries-gg
battery                                                        ftdi-vcp-driver                                                nordic-nrf-command-line-tools                                  stork
bazecor                                                        fujitsu-scansnap-home                                          nordlayer                                                      submariner
beardie                                                        fx-cast-bridge                                                 northern-softworks-cache-cleaner                               superkey
beast2                                                         fxfactory                                                      notch-simulator                                                superlist
bespoke                                                        gama                                                           notesnook                                                      supermjograph
betterandbetter                                                gama-jdk                                                       notion-enhanced                                                supernotes
betterdiscord-installer                                        gamemaker                                                      notunes                                                        surge-xt
betterdisplay                                                  gamma-control                                                  nudge                                                          swift-quit
betterdummy                                                    gaphor                                                         oak9                                                           swiftcord
bettermouse                                                    garmin-express                                                 obs-advanced-scene-switcher                                    swiftplantumlapp
biglybt                                                        gcc-aarch64-embedded                                           obsbot-webcam                                                  synology-cloud-station-backup
bike                                                           gcs                                                            oka-unarchiver                                                 synology-drive
bili-downloader                                                gdevelop                                                       onekey                                                         synology-photo-station-uploader
billings-pro                                                   genesis-plus                                                   only-switch                                                    synology-surveillance-station-client
bing-wallpaper                                                 genesys-cloud                                                  opal                                                           synologyassistant
binocs                                                         gitdock                                                        open-video-downloader                                          tablecruncher
black-ink                                                      gitkraken-cli                                                  openbb-terminal                                                tachidesk-sorayomi
black-light                                                    gittyup                                                        openbci                                                        tageditor
black-light-pro                                                glance-chamburr                                                opencore-patcher                                               tailscale
blender-benchmark                                              go-shiori                                                      openin                                                         tastytrade
blockbench                                                     google-assistant                                               openlens                                                       tdr-kotelnikov
bloop                                                          google-chat-electron                                           openrgb                                                        tdr-nova
bluebubbles                                                    goxel                                                          openrocket                                                     tdr-vos-slickeq
bluos-controller                                               gpgfrontend                                                    openshift-client                                               tea
blurscreen                                                     graalvm-jdk                                                    opensoundmeter                                                 teamspeak-client
bookletcreator                                                 grammarly-desktop                                              orangedrangon-android-messages                                 teleport-connect
bookwright                                                     gridtracker                                                    orbstack                                                       tempbox
bose-updater                                                   groestlcoin-core                                               orcaslicer                                                     temurin
breitbandmessung                                               grs-bluewallet                                                 orion                                                          tentacle-sync-studio
bridge                                                         gutenprint                                                     orka-vm-tools                                                  tev
bruno                                                          gyroflow                                                       oso-cloud                                                      texifier
buckets                                                        hackolade                                                      osp-tracker                                                    textsniper
bugdom                                                         hdfview                                                        osu                                                            thangs-sync
buzz                                                           hdhomerun                                                      otto-matic                                                     the-watcher
cad-assistant                                                  headlamp                                                       overt                                                          thetimemachinemechanic
caldigit-docking-utility                                       height                                                         pallotron-yubiswitch                                           thinlinc-client
caldigit-thunderbolt-charging                                  hepta                                                          panwriter                                                      threema
calhash                                                        heroic                                                         paperpile                                                      threema-work
cameracontroller                                               hidock                                                         paragon-camptune                                               ti-smartview-ce-for-the-ti-84-plus-family
canon-eos-utility                                              hookmark                                                       pdfify                                                         tic80
capacities                                                     hostsx                                                         pensela                                                        tidelift
capslocknodelay                                                hp-easy-start                                                  philips-hue-sync                                               tidgi
carbide-create                                                 html-mangareader                                               phpwebstudy                                                    tiptoi-manager
cardinal                                                       httpie                                                         picfindr                                                       tl-legacy
cardpresso                                                     huiontablet                                                    pichon                                                         tmpdisk
centered                                                       hummingbird                                                    piclist                                                        todesk
chatbox                                                        hydrus-network                                                 picoscope                                                      todoist
chipmunk                                                       icon-shelf                                                     pictureview                                                    toland-qlmarkdown
chromium-gost                                                  iconchamp                                                      pieces-cli                                                     tomatobar
cider                                                          iconchanger                                                    pingnoo                                                        topaz-denoise-ai
cirrus                                                         ideamaker                                                      planet                                                         topaz-gigapixel-ai
cisdem-duplicate-finder                                        imagex                                                         playcover-community                                            topaz-sharpen-ai
citrix-workspace                                               imazing-converter                                              playdate-simulator                                             topaz-video-ai
clay                                                           imhex                                                          plex-htpc                                                      topnotch
cleaneronepro                                                  infra                                                          plugdata                                                       toshiba-color-mfp
cleanmymac-zh                                                  inkstitch                                                      pluginval                                                      tqsl
clips-ide                                                      input-source-pro                                               plus42-binary                                                  trackerzapper
cloud189                                                       inso                                                           plus42-decimal                                                 trex
cloudash                                                       insta360-studio                                                podman-desktop                                                 trivial
clover                                                         interact-scratchpad                                            podpisuj                                                       trunk-io
codeedit                                                       iptvnator                                                      pokemon-tcg-live                                               tsh
codeql                                                         iqmol                                                          poker-copilot                                                  tuist
codux                                                          irpf2023                                                       pololu-avr-programmer-v2                                       twitch-studio
coffitivity-offline                                            izotope-product-portal                                         polypad                                                        typcn-bilibili
coherence-x                                                    jabra-direct                                                   polypane                                                       ubiquiti-unifi-controller
color-studio                                                   jetbrains-gateway                                              postman-agent                                                  uhk-agent
command-x                                                      jpc-qlcolorcode                                                postman-cli                                                    ui
concept2-utility                                               jquake                                                         ppsspp                                                         ukrainian-typographic-keyboard
confectionery                                                  jt-bridge                                                      prism                                                          ulbow
confluent-cli                                                  juice                                                          prismlauncher                                                  ultimate-vocal-remover
contour                                                        jump-desktop-connect                                           privadovpn                                                     ultracopier
copilot                                                        jupyterlab                                                     processmonitor                                                 unicopedia-plus
copilot-for-xcode                                              karafun                                                        projector                                                      unipro-ugene
corsair-icue                                                   kdenlive                                                       prolific-pl2303                                                unite-phone
craft                                                          kdrive                                                         protokol                                                       universal-android-debloater
creality-slicer                                                keet                                                           protonmail-import-export                                       universal-gcode-platform
creative                                                       keycombiner                                                    prowlarr                                                       unraid-usb-creator
cro-mag-rally                                                  keyman                                                         psst                                                           usmart-trade
cron                                                           keysafe                                                        pulsar                                                         uvtools
cursor                                                         kigb                                                           pure-writer                                                    v2ray-unofficial
cursr                                                          kiibohd-configurator                                           qflipper                                                       valkyrie
dadroit-json-viewer                                            kindavim                                                       qmk-toolbox                                                    vbrokers
datasette                                                      kmeet                                                          qspace-pro                                                     ved
dataspell                                                      konica-minolta-bizhub-c750i-driver                             qth                                                            vero
dbeaverlite                                                    konica-minolta-bizhub-c759-c658-c368-c287-c3851-driver         quarto                                                         vertcoin-core
dbeaverultimate                                                kopiaui                                                        quiet-reader                                                   videoduke
dbgate                                                         laconvolver                                                    quit-all                                                       vieb
dcp-o-matic-combiner                                           languagetool                                                   qwerty-fr                                                      vincelwt-chatgpt
dcp-o-matic-disk-writer                                        lapce                                                          rancher                                                        virtual-desktop-streamer
dcp-o-matic-editor                                             lasso                                                          random-mouse-clicker                                           virtualbuddy
dcp-o-matic-playlist-editor                                    leapp                                                          rapidapi                                                       vivid
ddpm                                                           lectrote                                                       readdle-spark                                                  vk-calls
decentr                                                        lemonlime                                                      readmoreading                                                  vlc-setup
deepnest                                                       letter-opener                                                  readwise-ibooks                                                volley
defold                                                         lg-onscreen-control                                            readyapi                                                       volta
dehelper                                                       libcblite                                                      rectangle-pro                                                  vpn-by-google-one
descript                                                       libcblite-community                                            red-canary-mac-monitor                                         vpn-tracker-365
detail                                                         linearmouse                                                    redquits                                                       vym
devcleaner                                                     linn-konfig                                                    reflect                                                        wacom-tablet
devpod                                                         live-home-3d                                                   reflex                                                         waltr-heic-converter
devsquadron                                                    livebook                                                       remarkable                                                     warp
devtoys                                                        llamachat                                                      reminders-menubar                                              watchfacestudio
diffusionbee                                                   lo-rain                                                        remix-ide                                                      wch-ch34x-usb-serial-driver
dintch                                                         localxpose                                                     remotehamradio                                                 weektodo
direqual                                                       logi-options-plus                                              remotion                                                       windterm
disk-diet                                                      logitech-camera-settings                                       replacicon                                                     wing-personal
displaylink                                                    logitech-g-hub                                                 restfox                                                        wirecast
dixa                                                           logitech-options                                               restream-chat                                                  wolai
dmg-canvas                                                     logitune                                                       reverso                                                        wondershare-edrawmax
dockview                                                       lookingglassbridge                                             revolver-office                                                wooshy
doll                                                           lookingglassstudio                                             rewind                                                         workman
doppler                                                        lotus                                                          ricochet-refresh                                               workspace-one-intelligent-hub
doughnut                                                       loupedeck                                                      ricoh-theta                                                    worldpainter
douyin                                                         ludwig                                                         rio                                                            wow
drata-agent                                                    lunacy                                                         rive                                                           wpsoffice-cn
drawpile                                                       lunasea                                                        rnnoise                                                        write
droidcam-obs                                                   lycheeslicer                                                   roam-research                                                  xemu
dropbox-capture                                                macast                                                         rockboxutility                                                 xiv-on-mac
duckduckgo                                                     macforge                                                       rode-connect                                                   xprocheck
duplicacy-cli                                                  macloggerdx                                                    roonbridge                                                     xstation5
dymo-label                                                     macmorpheus                                                    rsyncui                                                        xtool-creative-space
easydict                                                       macrorecorder                                                  runcat-plugins-manager                                         yandex-music-unofficial
ecamm-live                                                     macwhisper                                                     rustdesk                                                       yattee
edrawmind                                                      mail-assistant                                                 rwts-pdfwriter                                                 yealink-meeting
egnyte                                                         mana-security                                                  saleae-logic                                                   yousician
electrum-grs                                                   manila                                                         samsung-portable-ssd-t7                                        youtype
elephas                                                        manymc                                                         sanesidebuttons                                                yubico-authenticator
elephicon                                                      manyverse                                                      scatter                                                        yubico-yubikey-manager
elgato-camera-hub                                              mathcha-notebook                                               scene-maestro                                                  yubihsm2-sdk
elgato-control-center                                          mbcord                                                         scenica-player                                                 zed
elgato-game-capture-hd                                         mds                                                            schildichat                                                    zsa-wally

You have 15 outdated formulae and 2 outdated casks installed.

tektoncd-cli 0.17.1 is already installed but outdated (so it will be upgraded).
Warning: You are using macOS 10.15.
We (and Apple) do not provide support for this old version.
It is expected behaviour that some formulae will fail to build in this old version.
It is expected behaviour that Homebrew will be buggy and slow.
Do not create any issues about this on Homebrew's GitHub repositories.
Do not create any issues even if you think this message is unrelated.
Any opened issues will be immediately closed without response.
Do not ask for help from Homebrew or its maintainers on social media.
You may ask for help in Homebrew's discussions but are unlikely to receive a response.
Try to figure out the problem yourself and submit a fix as a pull request.
We will review it but may or may not accept it.

==> Fetching tektoncd-cli
==> Downloading https://ghcr.io/v2/homebrew/core/tektoncd-cli/manifests/0.20.0
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/tektoncd-cli/blobs/sha256:c27830c57e654803fb7a35dad330afc8085d72ac85249aa7fe10df8a94e3def2
##################################################################################################################################################################################################################################################### 100.0%
==> Upgrading tektoncd-cli
  0.17.1 -> 0.20.0 

==> Pouring tektoncd-cli--0.20.0.catalina.bottle.tar.gz
==> Caveats
zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/tektoncd-cli/0.20.0: 7 files, 54.5MB
==> Running `brew cleanup tektoncd-cli`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Removing: /usr/local/Cellar/tektoncd-cli/0.17.1... (7 files, 52.0MB)
==> `brew cleanup` has not been run in the last 30 days, running now...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
Removing: /Users/rgupta/Library/Caches/Homebrew/autoconf--2.71... (948.6KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/brotli--1.0.9... (1006.3KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/c-ares--1.17.1... (162.9KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/icu4c--69.1... (27.2MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/jemalloc--5.2.1_1... (641.8KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/libev--4.33... (146.0KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/libuv--1.42.0... (1.3MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/m4--1.4.18... (232.4KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/mpdecimal--2.5.1... (548.3KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/ncurses--6.2... (2.2MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/nghttp2--1.44.0... (965.1KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/node--16.6.1... (12.8MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/openjdk--16.0.1... (192.9MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/openssl@1.1--1.1.1k... (5.4MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/pkg-config--0.29.2_3... (234.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/tcl-tk--8.6.11_1... (8.5MB)
Removing: /Users/rgupta/Library/Caches/Homebrew/telnet--63.catalina.bottle.tar.gz... (55.0KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/tree--1.8.0... (49.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/watch--3.3.17... (37.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/node_bottle_manifest--16.6.1... (11.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/ncurses_bottle_manifest--6.2-1... (7.7KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/openjdk_bottle_manifest--16.0.1-1... (8.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/brotli_bottle_manifest--1.0.9... (6.6KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/watch_bottle_manifest--3.3.17... (5.4KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/descriptions.json... (315.8KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/helm_bottle_manifest--3.5.4... (4.3KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/jemalloc_bottle_manifest--5.2.1_1... (6.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/c-ares_bottle_manifest--1.17.1... (5.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/kubeseal_bottle_manifest--0.15.0... (4.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/python@3.8_bottle_manifest--3.8.10... (13.7KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/openssl@1.1_bottle_manifest--1.1.1k... (4.8KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/libuv_bottle_manifest--1.42.0... (5.4KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/azure-cli_bottle_manifest--2.23.0... (12KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/icu4c_bottle_manifest--69.1... (6.0KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/sqlite_bottle_manifest--3.35.5... (4.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/autoconf_bottle_manifest--2.71... (5.6KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/gdbm_bottle_manifest--1.19... (4.1KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/nghttp2_bottle_manifest--1.44.0... (7.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/tcl-tk_bottle_manifest--8.6.11_1... (6.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/libev_bottle_manifest--4.33... (5.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/ansible_bottle_manifest--3.4.0... (69.3KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/mpdecimal_bottle_manifest--2.5.1... (4.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/pyenv_bottle_manifest--1.2.27... (16.0KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/tree_bottle_manifest--1.8.0... (5.4KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/m4_bottle_manifest--1.4.18-1... (4.2KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/python@3.9_bottle_manifest--3.9.5... (12.5KB)
Removing: /Users/rgupta/Library/Caches/Homebrew/pkg-config_bottle_manifest--0.29.2_3... (4.7KB)
Removing: /Users/rgupta/Library/Logs/Homebrew/nghttp2... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/ncurses... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/libuv... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/jemalloc... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/brotli... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/icu4c... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/c-ares... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/openjdk... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/watch... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/node... (64B)
Removing: /Users/rgupta/Library/Logs/Homebrew/libev... (64B)
Removing: /usr/local/lib/python3.8/site-packages/__pycache__/sitecustomize.cpython-38.pyc... (1.4KB)
Removing: /usr/local/lib/python3.9/site-packages/__pycache__/easy_install.cpython-39.pyc... (292B)
Pruned 5 symbolic links and 3 directories from /usr/local
zsh: command not found: 📋
rgupta@rgupta-mac openshift-cicd-demo-1 % opc
zsh: command not found: opc
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn
CLI for tekton pipelines

Usage:
tkn [flags]
tkn [command]

Available Commands:
  bundle                Manage Tekton Bundles
  clustertask           Manage ClusterTasks
  clustertriggerbinding Manage ClusterTriggerBindings
  condition             Manage Conditions
  eventlistener         Manage EventListeners
  hub                   Interact with tekton hub
  pipeline              Manage pipelines
  pipelinerun           Manage PipelineRuns
  resource              Manage pipeline resources
  task                  Manage Tasks
  taskrun               Manage TaskRuns
  triggerbinding        Manage TriggerBindings
  triggertemplate       Manage TriggerTemplates

Other Commands:
  completion            Prints shell completion scripts
  version               Prints version information

Flags:
  -h, --help   help for tkn

Use "tkn [command] --help" for more information about a command.
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn logs
Error: command tkn logs doesn't exist. Run tkn help for available commands
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn pipelinerun
Manage PipelineRuns

Usage:
tkn pipelinerun [flags]
tkn pipelinerun [command]

Aliases:
  pipelinerun, pr, pipelineruns

Available Commands:
  cancel      Cancel a PipelineRun in a namespace
  delete      Delete PipelineRuns in a namespace
  describe    Describe a PipelineRun in a namespace
  list        Lists PipelineRuns in a namespace
  logs        Show the logs of a PipelineRun

Flags:
  -c, --context string      name of the kubeconfig context to use (default: kubectl config current-context)
  -h, --help                help for pipelinerun
  -k, --kubeconfig string   kubectl config file (default: $HOME/.kube/config)
  -n, --namespace string    namespace to use (default: from $KUBECONFIG)
  -C, --no-color            disable coloring (default: false)

Use "tkn pipelinerun [command] --help" for more information about a command.
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn pipelinerun -list
Error: unknown shorthand flag: 'l' in -list
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn pipelinerun list 
NAME                           STARTED         DURATION   STATUS
spring-petclinic-build-vz469   2 minutes ago   ---        Running
rgupta@rgupta-mac openshift-cicd-demo-1 % tkn pipelinerun logs
Pipeline still running ...
PipelineRun is still running: Tasks Completed: 2 (Failed: 0, Cancelled 0), Incomplete: 7, Skipped: 0
rgupta@rgupta-mac openshift-cicd-demo-1 % cd ~
rgupta@rgupta-mac ~ % find . -name kc
find: ./Library/Application Support/CallHistoryTransactions: Operation not permitted
find: ./Library/Application Support/com.apple.sharedfilelist: Operation not permitted
find: ./Library/Application Support/com.apple.TCC: Operation not permitted
find: ./Library/Application Support/FileProvider: Operation not permitted
find: ./Library/Application Support/CallHistoryDB: Operation not permitted
find: ./Library/Autosave Information: Operation not permitted
find: ./Library/IdentityServices: Operation not permitted
find: ./Library/Messages: Operation not permitted
find: ./Library/Sharing: Operation not permitted
find: ./Library/Mail: Operation not permitted
find: ./Library/Safari: Operation not permitted
find: ./Library/Suggestions: Operation not permitted
find: ./Library/Containers/com.apple.archiveutility: Operation not permitted
kfind: ./Library/Containers/com.apple.Safari: Operation not permitted
find: ./Library/Containers/com.apple.CloudDocs.MobileDocumentsFileProvider: Operation not permitted
find: ./Library/Containers/com.apple.news: Operation not permitted
find: ./Library/PersonalizationPortrait: Operation not permitted
find: ./Library/Metadata/CoreSpotlight: Operation not permitted
find: ./Library/Cookies: Operation not permitted
find: ./Library/Caches/CloudKit: Operation not permitted
find: ./Library/Caches/com.apple.ap.adprivacyd: Operation not permitted
find: ./.Trash: Operation not permitted
./Documents/principal/08-31/csc/documents/expenses/kc
rgupta@rgupta-mac ~ % argocd
zsh: command not found: argocd
rgupta@rgupta-mac ~ % brew install argocd
Running `brew update --auto-update`...
Warning: No available formula with the name "ca-certificates".
==> Searching for similarly named formulae and casks...
Error: No formulae or casks found for ca-certificates.
==> Auto-updated Homebrew!
Updated 1 tap (homebrew/core).
==> New Formulae
aarch64-elf-binutils           clang-build-analyzer           fdroidcl                       inih                           lighthouse                     open62541                      rome                           tidy-viewer
aarch64-elf-gcc                clang-format@11                felinks                        inotify-tools                  lilypond                       openai-whisper                 rospo                          tilt
aarch64-elf-gdb                clickhouse-cpp                 fend                           install-peerdeps               linode-cli                     opencl-clhpp-headers           rpki-client                    tinysearch
abi-compliance-checker         clickhouse-odbc                ferium                         interface99                    linux-headers@5.15             opencl-headers                 rslint                         tkey-ssh-agent
abi-dumper                     clifm                          feroxbuster                    iodine                         linux-headers@5.16             opencl-icd-loader              rtx                            tl-expected
abricate                       clipboard                      ffmpeg@4                       ipget                          liqoctl                        opendht                        ruby@3.0                       tlsx
access                         clitest                        ffmpeg@5                       iproute2                       lit                            openfga                        ruby@3.1                       toml-test
acl                            clive                          fgbio                          iptables                       litani                         openiked                       ruff                           toml11
actionlint                     cloudflare-quiche              fheroes2                       iputils                        livekit                        openjdk@17                     rune                           totp-cli
ada-url                        cloudflare-wrangler2           firefoxpwa                     isa-l                          livekit-cli                    openliberty-jakartaee9         rure                           touca
adamstark-audiofile            cloudflared                    fisher                         ivtools                        llama                          openliberty-webprofile9        rush-parallel                  toxcore
adr-viewer                     cloudiscovery                  flagd                          jackett                        llvm@12                        opensearch-dashboards          rustfmt                        tproxy
aftman                         cloudpan189-go                 flamebearer                    jaq                            llvm@13                        openssl@3                      rye                            tracy
age                            cloudprober                    flavours                       java-service-wrapper           llvm@14                        openssl@3.0                    sad                            tradcpp
age-plugin-yubikey             clusterawsadm                  flix                           jbang                          llvm@15                        opentelemetry-cpp              safeint                        treefmt
agg                            cmake-docs                     flock                          jdtls                          lmfit                          openvi                         sail                           tremor-runtime
aichat                         cmctl                          flyctl                         jellyfish                      lndir                          openvino                       salt-lint                      trezor-bridge
aicommits                      cntb                           fnlfmt                         jet                            localtunnel                    ord                            sambamba                       trippy
airspyhf                       cocogitto                      fnt                            jj                             locust                         osc-cli                        sapling                        trivy
aiven-client                   code-cli                       fonts-encodings                jless                          lowdown                        osv-scanner                    scala@2.13                     trurl
akku                           cog                            forgit                         joern                          lpeg                           ots                            scalingo                       trust-dns
alembic                        colima                         form                           johnnydep                      ls-lint                        ouch                           schemathesis                   trzsz
aliyunpan                      commitlint                     fortls                         joker                          ltex-ls                        pacmc                          scip                           trzsz-go
all-repos                      compiledb                      fortran-language-server        joplin-cli                     lua-language-server            page                           scrapy                         tsduck
alpscore                       conan@1                        fourmolu                       joshuto                        luacheck                       pam-reattach                   scriptisto                     tt
amber                          conda-lock                     fprettify                      jpdfbookmarks                  luau                           pandemics                      sdl2_sound                     ttdl
ancient                        conda-zsh-completion           fred                           jreleaser                      lucky-commit                   papilo                         seaweedfs                      ttmath
animdl                         conduit                        freebayes                      jscpd                          lunar-date                     pari-elldata                   secp256k1                      tuc
ansible-language-server        conman                         fst                            jsign                          lunzip                         pari-galdata                   selene                         tuntox
ansible@6                      convco                         fuego-firestore                jsmn                           ly                             pari-galpol                    service-weaver                 tut
ansible@7                      copa                           fypp                           json2tsv                       lziprecover                    pari-nflistdata                seven-kingdoms                 twm
ansilove                       copier                         g2o                            jsonschema                     m1ddc                          pari-seadata                   sevenzip                       twty
antidote                       core-lightning                 garble                         judy                           mabel                          pari-seadata-big               sextractor                     txt2man
apache-pulsar                  corepack                       gat                            juicefs                        maclaunch                      pax                            sftpgo                         tygo
apko                           corrosion                      gator                          juliaup                        macpine                        payload-dumper-go              sgn                            typescript-language-server
apophenia                      cosign                         gaze                           jupp                           mailcatcher                    pbzx                           sgr                            typewritten
apt                            countdown                      gcc@11                         k2tf                           mailsy                         pdf-diff                       shaderc                        typical
aptos                          coursier                       gcc@12                         kalign                         manifest-tool                  pdf2djvu                       shadowsocks-rust               typos-cli
ares                           cpi                            gcem                           kdoctor                        mapproxy                       pferd                          shodan                         typst
argparse                       cpp-httplib                    gdrive-downloader              keploy                         mariadb@10.10                  pfetch-rs                      shub                           uftrace
aribb24                        cppinsights                    gebug                          keyring                        mariadb@10.11                  pg_cron                        shush                          ugit
arjun                          cpptoml                        gemgen                         kics                           mariadb@10.6                   pg_partman                     sigrok-cli                     ulfius
arkade                         cppzmq                         geometry                       kitex                          mariadb@10.7                   pget                           simdutf                        unisonlang
artillery                      cpufetch                       getmail6                       kmod                           mariadb@10.8                   pgsync                         sing-box                       unxip
arttime                        cpuid                          gf                             kn                             mariadb@10.9                   pgvector                       singularity                    urlwatch
arxiv_latex_cleaner            cql-proxy                      gffread                        koka                           markdown-toc                   phoneinfoga                    skaffold@1.39                  usbutils
ascii2binary                   create-api                     gfold                          kopia                          markdownlint-cli2              php@8.0                        skeema                         utftex
ast-grep                       crfsuite                       ghc@8.10                       ksops                          marksman                       php@8.1                        slither-analyzer               uthash
astgen                         cri-tools                      ghc@9.2                        kt-connect                     mbt                            phrase-cli                     slsa-verifier                  uutils-findutils
astro                          criterion                      ghcup                          kube-score                     mbw                            picotool                       smap                           uuu
asyncapi                       cruft                          ghorg                          kubefirst                      mcap                           pinocchio                      smartdns                       uvg266
ata                            crytic-compile                 ghostunnel                     kubekey                        mcfly                          pinot                          smug                           valijson
atlas                          csview                         gi-docgen                      kubent                         mdless                         pint                           snakefmt                       vcluster
atmos                          ctlptl                         git-big-picture                kubernetes-cli@1.22            mdt                            pip-audit                      snapcast                       vectorscan
atop                           cue                            git-branchless                 kubescape                      mdzk                           pip-tools                      sniffer                        verapdf
autocannon                     curlcpp                        git-cliff                      kubesess                       meek                           pipdeptree                     sniffnet                       vermin
autocorrect                    cwb3                           git-codereview                 kubeval                        melange                        pipe-rename                    snowball                       verovio
aws-amplify                    cxgo                           git-credential-libsecret       kubevious                      melody                         pixie                          snowflake                      vespa-cli
aws-auth                       cyral-gimme-db-token           git-credential-oauth           kustomizer                     mesheryctl                     pixiewps                       socket_vmnet                   vhs
aws-nuke                       czg                            git-delete-merged-branches     kuttl                          meta-package-manager           pkcs11-tools                   solana                         victoriametrics
aws-sam-cli                    d2                             git-machete                    kwctl                          metalang99                     pkg-config-wrapper             solargraph                     viddy
aws-sso-cli                    dagger                         git-svn                        kwok                           metals                         pkgconf                        solc-select                    video-compare
aws-sso-util                   dart-sdk                       git-sync                       kyverno                        metview                        pluto                          solhint                        vile
aws-vault                      datafusion                     git-tools                      lacework-cli                   micro_inetd                    plz-cli                        sophus                         vineyard
aws2-wrap                      datatype99                     git-workspace                  lastz                          micromamba                     pmtiles                        soplex                         virt-manager
bartib                         datree                         gitlab-ci-local                ld-find-code-refs              microsocks                     poac                           souffle                        virtualfish
base16384                      dbml-cli                       gitoxide                       leapp-cli                      millet                         pocketbase                     spago                          vite
bash-language-server           ddcutil                        glibc@2.13                     leetup                         mimalloc                       pocl                           spdx-sbom-generator            viu
bashate                        ddh                            glider                         lemmeknow                      mimirtool                      pocsuite3                      spectral-cli                   vkectl
basis_universal                ddns-go                        gmssl                          levant                         minigraph                      podman-compose                 speedbump                      votca
bat-extras                     debugbreak                     gnustep-base                   lexicon                        minimap2                       podsync                        spek                           vsce
bazarr                         define                         go-camo                        lgeneral                       mkfontscale                    poke                           spidermonkey@78                vscode-langservers-extracted
bbtools                        devcontainer                   go-critic                      libabigail                     mkp224o                        pomsky                         spirv-headers                  vtable-dumper
bdftopcf                       dexter                         go-feature-flag-relay-proxy    libabw                         mle                            popeye                         spirv-llvm-translator          vue-cli
benerator                      difftastic                     go-task                        libadwaita                     mmtabbarview                   portablegl                     spot                           vulkan-extensionlayer
berkeley-db@5                  distrobox                      go@1.16                        libaec                         mods                           portal                         spotify_player                 vulkan-loader
bfgminer                       djhtml                         go@1.17                        libansilove                    mold                           postgraphile                   spr                            vulkan-tools
biber                          docker-buildx                  go@1.18                        libapplewm                     mongodb-atlas-cli              postgresql@13                  sql-language-server            vulkan-validationlayers
bindgen                        doggo                          go@1.19                        libaribcaption                 monika                         postgresql@15                  sql-migrate                    vvdec
bioperl                        dooit                          goawk                          libavif                        mpfrcx                         powerman-dockerize             sqlcmd                         vvenc
bk                             dotbot                         gobackup                       libbpf                         mprocs                         primecount                     sqlfluff                       wally
bkt                            dotdrop                        goctl                          libclc                         mqttui                         procps                         sqls                           wasm-micro-runtime
blocky                         dotnet@6                       gokart                         libcython                      mrbayes                        procps@3                       sse2neon                       wasm-tools
boolector                      dpp                            gokey                          libdivide                      msgpack-cxx                    protobuf@21                    sshs                           waybackpy
boost@1.76                     drill                          golines                        libdvbcsa                      mt32emu                        protobuf@3                     ssocr                          wazero
bore-cli                       dronedb                        gomodifytags                   libeatmydata                   mu-repo                        protolint                      stackql                        wb32-dfu-updater_cli
bossa                          dsda-doom                      goplus                         libecpint                      muon                           prowler                        stanc3                         weasyprint
bottom                         dsq                            goproxy                        libemf2svg                     murex                          proxsuite                      standard                       webkitgtk
brev                           dstack                         gops                           libfastjson                    musikcube                      prr                            staq                           webp-pixbuf-loader
brigade-cli                    dtm                            got                            libff                          mxnet                          prs                            statix                         websocketpp
brpc                           dtools                         gotests                        libfyaml                       mycorrhiza                     psysh                          steampipe                      weggli
btop                           dtrx                           gotestsum                      libgedit-gtksourceview         mypaint-brushes                purescript-language-server     stencil                        werf
btrfs-progs                    dufs                           gotify                         libgit2@1.5                    naga-cli                       pycparser                      stepci                         west
bubblewrap                     dump1090-mutability            gradle@7                       libgrape-lite                  nali                           pygit2                         streamvbyte                    wikibase-cli
buf                            dumpling                       grafana-agent                  libgrapheme                    naml                           pymol                          stuffbin                       wordle
burst                          dunamai                        grammarly-languageserver       libint                         nanoflann                      pymupdf                        stylelint                      wpebackend-fdo
busted                         dura                           grantlee                       libisofs                       nap                            pyoxidizer                     stylish-haskell                wxlua
bvm                            dutree                         graphqxl                       liblbfgs                       nb                             pypy3.10                       svlint                         wzprof
bwidget                        dynaconf                       grayskull                      liblerc                        ncnn                           pypy3.9                        svls                           x86_64-linux-gnu-binutils
bzip3                          dynein                         groestlcoin                    liblxi                         nemu                           python-build                   svt-av1                        xauth
c                              dynomite                       grpc@1.54                      libmarpa                       neovide                        python-gdbm@3.11               swift-outdated                 xbyak
c2rust                         dzr                            grype                          libmediainfo                   neovim-qt                      python-lsp-server              swiftdraw                      xcdiff
ca-certificates                easeprobe                      gtop                           libmng                         nerdctl                        python-tk@3.10                 swiftplantuml                  xcode-kotlin
camlp-streams                  ecflow-ui                      guile-gnutls                   libnetfilter_conntrack         nerdfix                        python-tk@3.11                 swtpm                          xcodes
canfigger                      echidna                        gum                            libnftnl                       netcdf-cxx                     python-toml                    syft                           xctesthtmlreport
cargo-about                    ecoji                          gyb                            libnghttp2                     netcdf-fortran                 python-typing-extensions       symengine                      xdg-ninja
cargo-bloat                    edencommon                     h2c                            libnl                          netmask                        python@3.10                    symlinks                       xinit
cargo-bundle                   editorconfig-checker           has                            libobjc2                       newrelic-infra-agent           python@3.11                    synergy-core                   xkbcomp
cargo-crev                     eget                           hatch                          libomemo-c                     nexttrace                      pyyaml                         syslog-ng                      xkcd
cargo-deny                     eigenpy                        hck                            libpaho-mqtt                   nftables                       qbe                            tagref                         xmodmap
cargo-depgraph                 elfx86exts                     helix                          libpaper                       nickel                         qdmr                           tailscale                      xorg-server
cargo-generate                 elixir-ls                      helmify                        libplacebo                     nixpacks                       qsv                            tailwindcss-language-server    xpipe
cargo-llvm-lines               elvis                          hermit                         librasterlite2                 nmrpflash                      quantum++                      taplo                          xq
cargo-make                     emqx                           hexer                          librespot                      node@16                        quartz-wm                      tarlz                          xrdb
cargo-nextest                  enchive                        highs                          libretls                       node@18                        quick-lint-js                  tart                           xsel
cargo-outdated                 enex2notion                    highway                        librist                        notify                         quilt-installer                tbls                           xurls
cargo-release                  enpass-cli                     hivex                          libsais                        nsh                            quran                          tea                            xwin
cargo-udeps                    envd                           hof                            libsigrok                      ntfy                           qwt-qt5                        teip                           yamale
cargo-zigbuild                 epinio                         hotbuild                       libsigrokdecode                numdiff                        railway                        teku                           yaml-language-server
cascadia                       erdtree                        hpp-fcl                        libsolv                        nuraft                         rbw                            teller                         yamlfmt
cassandra@3                    erigon                         hq                             libsoup@2                      nvchecker                      rdb                            temporal                       yorkie
cava                           erlang@24                      htmlq                          libtpms                        oak                            red-tldr                       tere                           youplot
cbindgen                       erofs-utils                    httm                           libunibreak                    oauth2c                        redis@6.2                      terminalimageviewer            youtubeuploader
cdebug                         esbuild                        http-prompt                    liburing                       objconv                        regula                         tern                           yt-dlp
cdsclient                      esphome                        httpyac                        libvatek                       observerward                   release-it                     terraform-lsp                  zbctl
censys                         etcd-cpp-apiv3                 huggingface-cli                libvisual                      ocl-icd                        renovate                       terraform-rover                zf
cffi                           evernote-backup                hurl                           libvisual-plugins              ocm                            reproc                         terramate                      zk
cfonts                         evtx                           hut                            libvisual-projectm             ocmtoc                         req                            testkube                       zlint
cgif                           f2                             hwatch                         libwpe                         octobuild                      reshape                        tetra                          zls
chain-bench                    fann                           hysteria                       libxcrypt                      octosql                        resvg                          texlive                        zpaqfranz
charls                         fastfec                        hyx                            libxcvt                        odo-dev                        retdec                         textidote                      zrok
charmcraft                     fastfetch                      hz                             libxfont2                      oh-my-posh                     rio                            textract                       zsh-autocomplete
chatblade                      fastgron                       ibazel                         libxls                         ohdear-cli                     ripsecrets                     tfel                           zsh-autopair
check-jsonschema               fastnetmon                     ifacemaker                     libzen                         okta-aws-cli                   rizin                          tfk8s                          zsh-fast-syntax-highlighting
checkmake                      fastp                          iir1                           libzim                         okta-awscli                    rnr                            tfmigrate                      zx
chroma                         fastq-tools                    ijq                            license-eye                    ol                             roapi                          tfproviderlint
chrpath                        fb303                          imap-backup                    licensed                       onedrive                       roblox-ts                      tfschema
cilium-cli                     fbthrift                       imessage-exporter              licenseplist                   onlykey-agent                  rojo                           tfupdate
circumflex                     fclones                        imposm3                        licensor                       opal                           rollup                         thriftgo

You have 30 outdated formulae and 2 outdated casks installed.

Warning: You are using macOS 10.15.
We (and Apple) do not provide support for this old version.
It is expected behaviour that some formulae will fail to build in this old version.
It is expected behaviour that Homebrew will be buggy and slow.
Do not create any issues about this on Homebrew's GitHub repositories.
Do not create any issues even if you think this message is unrelated.
Any opened issues will be immediately closed without response.
Do not ask for help from Homebrew or its maintainers on social media.
You may ask for help in Homebrew's discussions but are unlikely to receive a response.
Try to figure out the problem yourself and submit a fix as a pull request.
We will review it but may or may not accept it.

==> Fetching dependencies for argocd: go, ca-certificates, openssl@3, readline, sqlite, xz, python@3.11, cmake, c-ares, icu4c, libnghttp2, m4, automake, libtool, docutils, pygments, sphinx-doc, libuv, node and yarn
==> Fetching go
==> Downloading https://storage.googleapis.com/golang/go1.17.13.darwin-amd64.tar.gz
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://go.dev/dl/go1.20.5.src.tar.gz
==> Downloading from https://dl.google.com/go/go1.20.5.src.tar.gz
##################################################################################################################################################################################################################################################### 100.0%
==> Fetching ca-certificates
Warning: Using --insecure with curl to download `ca-certificates` because we need it installed to download securely from now on. Checksums will still be verified.
==> Downloading https://curl.se/ca/cacert-2023-05-30.pem
##################################################################################################################################################################################################################################################### 100.0%
==> Fetching openssl@3
==> Downloading https://github.com/openssl/openssl/commit/50af7294e514a2aba19c5248a4ed612ba3ba4c1b.patch?full_index=1
##################################################################################################################################################################################################################################################### 100.0%
Error: argocd: Failed to download resource "openssl@3"
Failure while executing; `/usr/bin/env /usr/local/Homebrew/Library/Homebrew/shims/shared/curl --disable --cookie /dev/null --globoff --show-error --user-agent Homebrew/4.0.26\ \(Macintosh\;\ Intel\ Mac\ OS\ X\ 10.15.5\)\ curl/7.64.1 --header Accept-Language:\ en --retry 3 --fail --location --silent --head https://www.openssl.org/source/openssl-3.1.1.tar.gz` exited with 60. Here's the output:
curl: (60) SSL certificate problem: certificate has expired
More details here: https://curl.haxx.se/docs/sslcerts.html

curl failed to verify the legitimacy of the server and therefore could not
establish a secure connection to it. To learn more about this situation and
how to fix it, please visit the web page mentioned above.


rgupta@rgupta-mac ~ % 
  [Restored Jul 10, 2023 at 9:27:20 AM]
Last login: Mon Jul  3 07:58:20 on console
rgupta@rgupta-mac ~ % clear

rgupta@rgupta-mac ~ % ls
Applications	Desktop		Documents	Downloads	Library		Movies		Music		Pictures	Public		VirtualBox VMs
rgupta@rgupta-mac ~ % pwd
/Users/rgupta
rgupta@rgupta-mac ~ % cd Documents 
rgupta@rgupta-mac Documents % ls
L-What's%20New%20in%20OpenShift%20Container%20Platform%204.7.pptx_0.odp	expenses								openshift
WebEx									keycloak								personal
accounts								mcclane									principal
rgupta@rgupta-mac Documents % cd accounts 
rgupta@rgupta-mac accounts % ls
Maimonides			bankofhawaii			crown				discount			iodine				svgtopng (1)			thirdfederal
Video_20230707_191207_174.mp4	cd.png				d.svg				doxy-2023.3gp			laird				svgtopng (1).zip		zions bank
alegro				cerberus			demo.png			evolveip			max				svgtopng.zip
an.jpeg				cig				demo.svg			ibm-2				myriad				techm
rgupta@rgupta-mac accounts % mkdir mclane
rgupta@rgupta-mac accounts % cd mclane 
rgupta@rgupta-mac mclane % git clone https://github.com/siamaksade/openshift-cicd-demo
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
rgupta@rgupta-mac mclane % git clone https://github.com/siamaksade/openshift-cicd-demo.git
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
rgupta@rgupta-mac mclane % git
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
rgupta@rgupta-mac mclane % ls
rgupta@rgupta-mac mclane % brew install git
==> Downloading https://formulae.brew.sh/api/formula.jws.json
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://formulae.brew.sh/api/cask.jws.json
##################################################################################################################################################################################################################################################### 100.0%
==> Fetching dependencies for git: gettext and pcre2
==> Fetching gettext
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/manifests/0.21.1
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/blobs/sha256:fd7e48065cf73e37dfdf4c5cb789a14b93cf58ac06060814a60c94b87d8f26e6
##################################################################################################################################################################################################################################################### 100.0%
==> Fetching pcre2
==> Downloading https://ghcr.io/v2/homebrew/core/pcre2/manifests/10.42
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pcre2/blobs/sha256:7f414ed9d561dc85aacd41c7d18a452d3f58a6fe73af02b8fb876483080ec4df
##################################################################################################################################################################################################################################################### 100.0%
==> Fetching git
==> Downloading https://ghcr.io/v2/homebrew/core/git/manifests/2.41.0_1
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/git/blobs/sha256:6b23e127ff57cb08b6e610bf9805cc5ba8169a3ff55c8cc79bb00e3aa0507856
##################################################################################################################################################################################################################################################### 100.0%
==> Installing dependencies for git: gettext and pcre2
==> Installing git dependency: gettext
==> Pouring gettext--0.21.1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/gettext/0.21.1: 1,983 files, 20.3MB
==> Installing git dependency: pcre2
==> Pouring pcre2--10.42.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/pcre2/10.42: 230 files, 6.3MB
==> Installing git
==> Pouring git--2.41.0_1.ventura.bottle.tar.gz
==> Caveats
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.

zsh completions and functions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/git/2.41.0_1: 1,633 files, 48.7MB
==> Running `brew cleanup git`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Caveats
==> git
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.

zsh completions and functions have been installed to:
  /usr/local/share/zsh/site-functions
rgupta@rgupta-mac mclane % git
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
rgupta@rgupta-mac mclane % brew instlal xcrun
Error: Unknown command: instlal
rgupta@rgupta-mac mclane % brew instlal xcrun
Error: Unknown command: instlal
rgupta@rgupta-mac mclane % brew install xcrun
Running `brew update --auto-update`...
Warning: No available formula with the name "xcrun". Did you mean crun?
==> Downloading https://formulae.brew.sh/api/formula_tap_migrations.jws.json
##################################################################################################################################################################################################################################################### 100.0%
==> Downloading https://formulae.brew.sh/api/cask_tap_migrations.jws.json
##################################################################################################################################################################################################################################################### 100.0%
==> Searching for similarly named formulae and casks...
Error: No formulae or casks found for xcrun.
rgupta@rgupta-mac mclane % git
xcrun: error: invalid active developer path (/Library/Developer/CommandLineTools), missing xcrun at: /Library/Developer/CommandLineTools/usr/bin/xcrun
rgupta@rgupta-mac mclane % xcode-select --install
xcode-select: note: install requested for command line developer tools
rgupta@rgupta-mac mclane % git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
rgupta@rgupta-mac mclane % git clone https://github.com/siamaksade/openshift-cicd-demo.git
Cloning into 'openshift-cicd-demo'...
remote: Enumerating objects: 321, done.
remote: Counting objects: 100% (138/138), done.
remote: Compressing objects: 100% (40/40), done.
remote: Total 321 (delta 109), reused 107 (delta 98), pack-reused 183
Receiving objects: 100% (321/321), 1.44 MiB | 5.65 MiB/s, done.
Resolving deltas: 100% (180/180), done.
rgupta@rgupta-mac mclane % oc login https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/oauth/token/request
rgupta@rgupta-mac mclane % oc login --token=sha256~K7KTBLLq948FgIiKXT6H8nb2Wu0A64ffrd8HCY4QzVs --server=https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443" as "admin" using the token provided.

You have access to 67 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac mclane % ls
onsite			openshift-cicd-demo
rgupta@rgupta-mac mclane % cd openshift-cicd-demo 
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % oc new-project demo
Now using project "demo" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo % ./ demo.sh install
zsh: permission denied: ./
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
W0710 14:58:21.620179   26025 warnings.go:70] would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "postgresql" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "postgresql" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "postgresql" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "postgresql" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
W0710 14:58:22.065203   26025 warnings.go:70] would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "gitea" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "gitea" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "gitea" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "gitea" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
W0710 14:58:22.510169   26025 warnings.go:70] would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "nexus" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "nexus" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "nexus" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "nexus" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
W0710 14:58:23.102572   26025 warnings.go:70] would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "sonarqube" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "sonarqube" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "sonarqube" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "sonarqube" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): namespaces "openshift-pipelines" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   9m36s
NAME       STATUS   AGE
demo-dev   Active   9m35s
NAME         STATUS   AGE
demo-stage   Active   9m35s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   10m
NAME       STATUS   AGE
demo-dev   Active   10m
NAME         STATUS   AGE
demo-stage   Active   10m

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   66m
NAME       STATUS   AGE
demo-dev   Active   66m
NAME         STATUS   AGE
demo-stage   Active   66m

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
error: deployment "gitea" exceeded its progress deadline
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh delete

  Usage:
      demo [command] [options]

  Example:
      demo install --project-prefix mydemo

  COMMANDS:
      install                        Sets up the demo and creates namespaces
      uninstall                      Deletes the demo
      start                          Starts the deploy DEV pipeline
      help                           Help about this command

  OPTIONS:
      -p|--project-prefix [string]   Prefix to be added to demo project names e.g. PREFIX-dev
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh uninstall
project.project.openshift.io "demo-dev" deleted
project.project.openshift.io "demo-stage" deleted
project.project.openshift.io "demo-cicd" deleted
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install  

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS        AGE
demo-cicd   Terminating   108m
Now using project "demo-dev" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
Error from server (Forbidden): rolebindings.rbac.authorization.k8s.io "system:image-puller" is forbidden: unable to create new content in namespace demo-cicd because it is being terminated
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

NAME       STATUS   AGE
demo-dev   Active   104s
NAME         STATUS   AGE
demo-stage   Active   103s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-hdwwp created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.funeXlUb ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 2.17 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo 4141be5] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 457 bytes | 457.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/gitea/spring-petclinic
   aacbbb4..4141be5  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Already on project "demo-cicd" on server "https://api.cluster-bmf26.bmf26.sandbox348.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-bmf26.bmf26.sandbox348.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % opc pac logs -n demo-cicd
zsh: command not found: opc
rgupta@rgupta-mac openshift-cicd-demo % tkn 
CLI for tekton pipelines

Usage:
tkn [flags]
tkn [command]

Available Commands:
  bundle                Manage Tekton Bundles
  clustertask           Manage ClusterTasks
  clustertriggerbinding Manage ClusterTriggerBindings
  condition             Manage Conditions
  eventlistener         Manage EventListeners
  hub                   Interact with tekton hub
  pipeline              Manage pipelines
  pipelinerun           Manage PipelineRuns
  resource              Manage pipeline resources
  task                  Manage Tasks
  taskrun               Manage TaskRuns
  triggerbinding        Manage TriggerBindings
  triggertemplate       Manage TriggerTemplates

Other Commands:
  completion            Prints shell completion scripts
  version               Prints version information

Flags:
  -h, --help   help for tkn

Use "tkn [command] --help" for more information about a command.
rgupta@rgupta-mac openshift-cicd-demo % tkn pac logs -n demo-cicd
Error: unknown shorthand flag: 'n' in -n
rgupta@rgupta-mac openshift-cicd-demo % tkn pac logs -n demo-cicd
Error: unknown shorthand flag: 'n' in -n
rgupta@rgupta-mac openshift-cicd-demo % tkn logs -n demo-cicd
Error: unknown shorthand flag: 'n' in -n
rgupta@rgupta-mac openshift-cicd-demo % tkn pipeline -n demo-cicd
Manage pipelines

Usage:
tkn pipeline [flags]
tkn pipeline [command]

Aliases:
  pipeline, p, pipelines

Available Commands:
  delete      Delete Pipelines in a namespace
  describe    Describes a Pipeline in a namespace
  list        Lists Pipelines in a namespace
  logs        Show Pipeline logs
  start       Start Pipelines

Flags:
  -c, --context string      name of the kubeconfig context to use (default: kubectl config current-context)
  -h, --help                help for pipeline
  -k, --kubeconfig string   kubectl config file (default: $HOME/.kube/config)
  -n, --namespace string    namespace to use (default: from $KUBECONFIG)
  -C, --no-color            disable coloring (default: false)

Use "tkn pipeline [command] --help" for more information about a command.
rgupta@rgupta-mac openshift-cicd-demo % tkn pipeline logs -n demo-cicd
No Pipelines found in namespace demo-cicd%                                                                                                                                                                                                                  rgupta@rgupta-mac openshift-cicd-demo % oc login https://api.cluster-ldx2j.ldx2j.sandbox3112.opentlc.com:6443 
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-ldx2j.ldx2j.sandbox3112.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo % oc login https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo % oc login --token=sha256~LuPl_vxpCiJUez9l8cK15YP3MaYAgRieHopoIuTjAxM --server=https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443" as "admin" using the token provided.

You have access to 67 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac openshift-cicd-demo % oc new-project demo
Now using project "demo" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   2m30s
NAME       STATUS   AGE
demo-dev   Active   2m29s
NAME         STATUS   AGE
demo-stage   Active   2m29s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-jrl4x created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.koHEt7Lm ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 8.77 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo ce2139f] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 457 bytes | 457.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic
   aacbbb4..ce2139f  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % grep -R Welcome *
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % find . -name *.html
zsh: no matches found: *.html
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % cd ..
rgupta@rgupta-mac mclane % git clone http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic.git
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9320, done.
remote: Counting objects: 100% (9320/9320), done.
remote: Compressing objects: 100% (4459/4459), done.
remote: Total 9320 (delta 3584), reused 9299 (delta 3573), pack-reused 0
Receiving objects: 100% (9320/9320), 6.95 MiB | 8.48 MiB/s, done.
Resolving deltas: 100% (3584/3584), done.
rgupta@rgupta-mac mclane % ls
onsite			openshift-cicd-demo	spring-petclinic
rgupta@rgupta-mac mclane % cd spring-petclinic 
rgupta@rgupta-mac spring-petclinic % find . -name *.html
zsh: no matches found: *.html
rgupta@rgupta-mac spring-petclinic % find . -name *.java
zsh: no matches found: *.java
rgupta@rgupta-mac spring-petclinic % ls
LICENSE.txt		docker-compose.yml	gradlew			mvnw			pom.xml			settings.gradle
build.gradle		gradle			gradlew.bat		mvnw.cmd		readme.md		src
rgupta@rgupta-mac spring-petclinic % cd src
rgupta@rgupta-mac src % ls
checkstyle	main		test
rgupta@rgupta-mac src % find . -name *.mvn
zsh: no matches found: *.mvn
rgupta@rgupta-mac src % find . -name *.bat
zsh: no matches found: *.bat
rgupta@rgupta-mac src % find . -name *.cmd
zsh: no matches found: *.cmd
rgupta@rgupta-mac src % ls
checkstyle	main		test
rgupta@rgupta-mac src % cd main
rgupta@rgupta-mac main % ls
java		resources	scss
rgupta@rgupta-mac main % cd java
rgupta@rgupta-mac java % ls
org
rgupta@rgupta-mac java % cd *
rgupta@rgupta-mac org % ls
springframework
rgupta@rgupta-mac org % cd *
rgupta@rgupta-mac springframework % ls
samples
rgupta@rgupta-mac springframework % cd *
rgupta@rgupta-mac samples % ls
petclinic
rgupta@rgupta-mac samples % cd *
rgupta@rgupta-mac petclinic % ls
PetClinicApplication.java	model				owner				system				vet
rgupta@rgupta-mac petclinic % find . -name *.java
./PetClinicApplication.java
rgupta@rgupta-mac petclinic % cd ..
rgupta@rgupta-mac samples % cd ..
rgupta@rgupta-mac springframework % ls
samples
rgupta@rgupta-mac springframework % cd ..
rgupta@rgupta-mac org % ls
springframework
rgupta@rgupta-mac org % cd ..
rgupta@rgupta-mac java % ls
org
rgupta@rgupta-mac java % cd ..
rgupta@rgupta-mac main % ls
java		resources	scss
rgupta@rgupta-mac main % cd ..
rgupta@rgupta-mac src % ls
checkstyle	main		test
rgupta@rgupta-mac src % cd ..
rgupta@rgupta-mac spring-petclinic % ls
LICENSE.txt		docker-compose.yml	gradlew			mvnw			pom.xml			settings.gradle
build.gradle		gradle			gradlew.bat		mvnw.cmd		readme.md		src
rgupta@rgupta-mac spring-petclinic % grep -R welcome
Binary file ./.git/objects/pack/pack-bc9a178f6faaba0940b411377793f14e897929ff.pack matches
Binary file ./.git/index matches
./src/main/resources/messages/messages_de.properties:welcome=Willkommen
./src/main/resources/messages/messages_es.properties:welcome=Bienvenido
./src/main/resources/messages/messages.properties:welcome=Welcome
./src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java:	public String welcome() {
./src/main/java/org/springframework/samples/petclinic/system/WelcomeController.java:		return "welcome";
rgupta@rgupta-mac spring-petclinic % ls 
LICENSE.txt		docker-compose.yml	gradlew			mvnw			pom.xml			settings.gradle
build.gradle		gradle			gradlew.bat		mvnw.cmd		readme.md		src
rgupta@rgupta-mac spring-petclinic % ./demo.sh uninstall
zsh: no such file or directory: ./demo.sh
rgupta@rgupta-mac spring-petclinic % ls
LICENSE.txt		docker-compose.yml	gradlew			mvnw			pom.xml			settings.gradle
build.gradle		gradle			gradlew.bat		mvnw.cmd		readme.md		src
rgupta@rgupta-mac spring-petclinic % cd ..
rgupta@rgupta-mac mclane % ls
onsite			openshift-cicd-demo	spring-petclinic
rgupta@rgupta-mac mclane % cd openshift-cicd-demo 
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh uninstall   
project.project.openshift.io "demo-dev" deleted
project.project.openshift.io "demo-stage" deleted
project.project.openshift.io "demo-cicd" deleted
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install  

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Already on project "demo-cicd" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-jdpsw created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.iNn25Bw0 ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 6.32 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo a6c0d2b] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 458 bytes | 458.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic
   aacbbb4..a6c0d2b  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-lntgn.lntgn.sandbox3153.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-lntgn.lntgn.sandbox3153.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % oc login https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo % oc login --token=sha256~v0D7coEONj0YQ6AsuV3oQlbZ4LnjMuJnrgFAZftNKbs --server=https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443" as "admin" using the token provided.

You have access to 67 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): namespaces "openshift-pipelines" not found
rgupta@rgupta-mac openshift-cicd-demo % oc new-project demo
Now using project "demo" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo % oc new-project demo
Error from server (AlreadyExists): project.project.openshift.io "demo" already exists
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install  

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   2m49s
NAME       STATUS   AGE
demo-dev   Active   2m48s
NAME         STATUS   AGE
demo-stage   Active   2m47s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   3m42s
NAME       STATUS   AGE
demo-dev   Active   3m41s
NAME         STATUS   AGE
demo-stage   Active   3m40s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-dpwtd created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.Ly5ZKHDT ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 7.38 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo c285b89] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 456 bytes | 456.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic
   aacbbb4..c285b89  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % cd ..
rgupta@rgupta-mac mclane % ls
onsite			openshift-cicd-demo	spring-petclinic
rgupta@rgupta-mac mclane % cd spring-petclinic 
rgupta@rgupta-mac spring-petclinic % grep -R spring-pivotal-logo
Binary file ./.git/index matches
./src/main/resources/templates/fragments/layout.html:            <img src="../static/resources/images/spring-pivotal-logo.png"
./src/main/resources/templates/fragments/layout.html:              th:src="@{/resources/images/spring-pivotal-logo.png}" alt="Sponsored by Pivotal" /></div>
rgupta@rgupta-mac spring-petclinic % ./demo.sh uninstall        
zsh: no such file or directory: ./demo.sh
rgupta@rgupta-mac spring-petclinic % ls
LICENSE.txt		docker-compose.yml	gradlew			mvnw			pom.xml			settings.gradle
build.gradle		gradle			gradlew.bat		mvnw.cmd		readme.md		src
rgupta@rgupta-mac spring-petclinic % cd ..
rgupta@rgupta-mac mclane % ls
onsite			openshift-cicd-demo	spring-petclinic
rgupta@rgupta-mac mclane % cd openshift-cicd-demo 
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh uninstall   
project.project.openshift.io "demo-dev" deleted
project.project.openshift.io "demo-stage" deleted
project.project.openshift.io "demo-cicd" deleted
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install  

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Already on project "demo-cicd" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-jwm54 created
.

Waiting for source code to be imported to Gitea...
.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.QvUOVKnx ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 3.09 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo 57d5828] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 458 bytes | 458.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic
   aacbbb4..57d5828  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-srg5r.srg5r.sandbox3042.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-srg5r.srg5r.sandbox3042.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % pwd
/Users/rgupta/Documents/accounts/mclane/openshift-cicd-demo
rgupta@rgupta-mac openshift-cicd-demo % history
  601  ./demo.sh install
  602  ls
  603  cd ..
  604  ls
  605  cd spring-petclinic
  606  grep -R spring-pivotal-logo
  607  ./demo.sh uninstall
  608  ls
  609  cd ..
  610  ls
  611  cd openshift-cicd-demo
  612  ls
  613  ./demo.sh uninstall
  614  ./demo.sh install
  615  ls
  616  pwd
rgupta@rgupta-mac openshift-cicd-demo % clear

rgupta@rgupta-mac openshift-cicd-demo % oc login https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo % oc login --token=sha256~TyixdhZYtq8I40NEON_mnVV9UVA0FzGJidwhpnc1Q1o --server=https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443" as "admin" using the token provided.

You have access to 67 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac openshift-cicd-demo %  oc new-project demo
Now using project "demo" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   44s
NAME       STATUS   AGE
demo-dev   Active   43s
NAME         STATUS   AGE
demo-stage   Active   43s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-7h8ft created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.ybYvUm05 ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 6.77 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo fd98b3e] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 460 bytes | 460.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic
   aacbbb4..fd98b3e  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   15m
NAME       STATUS   AGE
demo-dev   Active   15m
NAME         STATUS   AGE
demo-stage   Active   15m

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   16m
NAME       STATUS   AGE
demo-dev   Active   16m
NAME         STATUS   AGE
demo-stage   Active   16m

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (AlreadyExists): error when creating "STDIN": configmaps "gitea-config" already exists
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh uninstall
project.project.openshift.io "demo-dev" deleted
project.project.openshift.io "demo-stage" deleted
project.project.openshift.io "demo-cicd" deleted
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install  

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Already on project "demo-cicd" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-72bgz created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.6wDbXp2e ~/Documents/accounts/mclane/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 4.85 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo 08811f5] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 460 bytes | 460.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic
   aacbbb4..08811f5  cicd-demo -> cicd-demo
~/Documents/accounts/mclane/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.

.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-9rnq5.9rnq5.sandbox2487.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % oc get nodee -o wide
error: the server doesn't have a resource type "nodee"
rgupta@rgupta-mac openshift-cicd-demo % oc get nodes -o wide
NAME                                         STATUS   ROLES                  AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                       KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-139-20.us-east-2.compute.internal    Ready    worker                 23h   v1.26.3+b404935   10.0.139.20    <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-161-47.us-east-2.compute.internal    Ready    control-plane,master   23h   v1.26.3+b404935   10.0.161.47    <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-163-148.us-east-2.compute.internal   Ready    worker                 23h   v1.26.3+b404935   10.0.163.148   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-191-180.us-east-2.compute.internal   Ready    control-plane,master   23h   v1.26.3+b404935   10.0.191.180   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-225-165.us-east-2.compute.internal   Ready    control-plane,master   23h   v1.26.3+b404935   10.0.225.165   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-241-202.us-east-2.compute.internal   Ready    worker                 23h   v1.26.3+b404935   10.0.241.202   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
rgupta@rgupta-mac openshift-cicd-demo % clear

rgupta@rgupta-mac openshift-cicd-demo % oc get nodes -o wide
NAME                                         STATUS   ROLES                  AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                       KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-139-20.us-east-2.compute.internal    Ready    worker                 23h   v1.26.3+b404935   10.0.139.20    <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-161-47.us-east-2.compute.internal    Ready    control-plane,master   23h   v1.26.3+b404935   10.0.161.47    <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-163-148.us-east-2.compute.internal   Ready    worker                 23h   v1.26.3+b404935   10.0.163.148   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-191-180.us-east-2.compute.internal   Ready    control-plane,master   23h   v1.26.3+b404935   10.0.191.180   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-225-165.us-east-2.compute.internal   Ready    control-plane,master   23h   v1.26.3+b404935   10.0.225.165   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
ip-10-0-241-202.us-east-2.compute.internal   Ready    worker                 23h   v1.26.3+b404935   10.0.241.202   <none>        Red Hat Enterprise Linux CoreOS 413.92.202305231734-0 (Plow)   5.14.0-284.13.1.el9_2.x86_64   cri-o://1.26.3-7.rhaos4.13.gitb3475fb.el9
rgupta@rgupta-mac openshift-cicd-demo % oc get nodes -o wide
error: You must be logged in to the server (Unauthorized)
rgupta@rgupta-mac openshift-cicd-demo % cd ~
rgupta@rgupta-mac ~ % ls
Applications	Desktop		Documents	Downloads	Library		Movies		Music		Pictures	Public		VirtualBox VMs
rgupta@rgupta-mac ~ % cd .ssh
rgupta@rgupta-mac .ssh % ls
book-import	config		id_rsa		id_rsa.pub	known_hosts
rgupta@rgupta-mac .ssh % vi id_rsa
rgupta@rgupta-mac .ssh % vi id_rsa.pub 
rgupta@rgupta-mac .ssh % oc login https://api.ocp4-c6d5q-ipi.azure.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.ocp4-c6d5q-ipi.azure.opentlc.com/oauth/token/request
rgupta@rgupta-mac .ssh % oc login --token=sha256~r09de6fCEqyg2xu6dAZQtIj1mxoqVjeaHogFpPqi6OY --server=https://api.ocp4-c6d5q-ipi.azure.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.ocp4-c6d5q-ipi.azure.opentlc.com:6443" as "admin" using the token provided.

You have access to 73 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
NDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTEyYURWck1pNTJhRFZyTWk1ellXNWtZbTk0T1RrMExtOXdaVzUwYkdNdVkyOXRPalkwTkRNS0lDQnVZVzFsT2lCa1pXWmhkV3gwTFdOc2RYTjBaWElLWTI5dWRHVjRkSE02Q2kwZ1kyOXVkR1Y0ZERvS0lDQWdJR05zZFhOMFpYSTZJR1JsWm1GMWJIUXRZMngxYzNSbGNnb2dJQ0FnYm1GdFpYTndZV05sT2lCa1pXWmhkV3gwQ2lBZ0lDQjFjMlZ5T2lCa1pXWmhkV3gwTFdGMWRHZ0tJQ0J1WVcxbE9pQmtaV1poZFd4MExXTnZiblJsZUhRS1kzVnljbVZ1ZEMxamIyNTBaWGgwT2lCa1pXWmhkV3gwTFdOdmJuUmxlSFFLYTJsdVpEb2dRMjl1Wm1sbkNuQnlaV1psY21WdVkyVnpPaUI3ZlFwMWMyVnljem9LTFNCdVlXMWxPaUJrWldaaGRXeDBMV0YxZEdnS0lDQjFjMlZ5T2dvZ0lDQWdkRzlyWlc0NklHVjVTbWhpUjJOcFQybEtVMVY2U1RGT2FVbHpTVzEwY0ZwRFNUWkpiVkY0VFVkNGJsSXlPVVJWUnpFMFlURk9SVk5IYUU1U2Vtc3lUVVpHZDFVeFdsQlJiR04wWlZob05WUXlWWHBUYVRGdFlWTXhXRTVFWjJsbVVTNWxlVXB3WXpOTmFVOXBTbkprVjBwc1kyMDFiR1JIVm5wTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1FbHBkMmxoTTFacFdsaEtkVnBZVW14amVUVndZbms1ZWxwWVNqSmhWMDVzV1ZkT2FtSXpWblZrUXpsMVdWY3hiR016UW1oWk1sVnBUMmxLYUdWdVZubGFWMDV6WkZoT01GcFlTV2xNUTBweVpGZEtiR050Tld4a1IxWjZURzFzZGt3elRteGpibHB3V1RKV2FGa3lUblprVnpVd1RETk9iRmt6U214a1F6VjFXVmN4YkVscWIybFpXSEF4WTIxV2FtSklWbnBrUjFaNVRGZEtkbUl6VW5wa1NFcG9ZME14ZWxsVE1UQmlNblJzWW1reGIyTllhSHBrZVVselNXMTBNVmx0Vm5saWJWWXdXbGhOZFdGWE9IWmpNbFo1Wkcxc2FscFhSbXBaTWpreFltNVJkbU15Vm5sa2JXeHFXbE14YUZreVRuWmtWelV3VEcwMWFHSlhWV2xQYVVwb1pXNVdlVnBYVG5Oa1dFNHdXbGhKZEZsdE9YWmtTRTR3WTIxR2QweFlUbWhKYVhkcFlUTldhVnBZU25WYVdGSnNZM2sxY0dKNU9YcGFXRW95WVZkT2JGbFhUbXBpTTFaMVpFTTVlbHBZU2pKaFYwNXNURmRHYWxreU9URmlibEYxWkZkc2EwbHFiMmxOZWtacVdsUlZNRnBVVVhST2VrRXhUbWt3TUZsNmFHdE1WMGt4V1hwcmRGcEhVVEpaZWxGNlQwZFZNRnBYVlRSSmFYZHBZek5XYVVscWIybGpNMng2WkVkV2RFOXVUbXhqYmxwd1dUSldhRmt5VG5aa1Z6VXdUMjFHTm1SWVNteFpNbmd4WXpOU2JHTnFjR2hsYmxaNVdsZE9jMlJZVGpCYVdFbDBXVzA1ZG1SSVRqQmpiVVozVEZoT2FFbHVNQzVIZEVsa1YwZFhja3hOVmpCSVJWVXdNVGxaWDJWbVJuZDBTMjVLUnpSSmJ6SkNZMlpoZVRWUFFUWnBhM05rVm5kTVZsTXpSMGhmVUhCVVJsTm1abnAxUkhrMlRqQmFiblkzUlc5b09EYzFWRUZIZDNWdmFrSlphRjlaTTFCeVdqQkpkMnMwV1ZKc1dFSkJiSG81WjFvelZXcFFUVFZVUzBwRVVrbGZjRjl4YkhOckxXdGtPVTgxVkRoU2Iwc3pSazFmVmtRMWQxRXhkekJTV1RCRU0wRXphSFV3TUhjek9EaHRZMFZKTVZwWFdIRnRUbHBaTXpKVk0wVXhiMmsyYVVZMlZYaGxZbmN4YlVsVmFFOU9Tak15TkZKamJtWTNUVGRKVEhVNFMxcE9VMjFVYWt0b1dDMHhZV1p5WVRkRVNqQm5NWEZOV25GSGIwaFpNR2RxTUVSYVZDMWlWMDlZWW5rd1ZEbEhhbGxIVFdsVlYwcGZVSGQyZFdwNVpWcEdkVkowUzNOa1kwb3RXVGxrVTJoUmNVcHhXa1I1VWxCUVVpMHlNVkJOVTBWa2VrVk1hSFp3UzBJMlgzWm5ZblE1ZGpCalRFVjJURmhQTVRSNWNGaE5MWEF0VWpWRWQwMTRiMEZXVUVzellXdHZaRGxDWjJWM05tTmZPVU5WWlVkbFdVRktUMFkxTlV4a1RXbHRhMmh4Tld4bFlsZGxURWx4VXpKcGFWQm1MVWN6WVc5NlRGbG1SbVJMUm01MmQyUlpaRjkzZVhOU1NYQjRaWFZMY1V0ZmJUTklZVGRmV2paRWVGSkVjMDgyZFVneGRVUnBTRmMzVW1kS2REVkNkMmgwUnpGRFpVdHdYM0JLVFhaeVMzQTNiMlU1VjBGS2FUWTRiM2xTYVRGVFNVTTFUM3BXT0hGM2JscHBjM1psU0c4NGQzaFdlVlpEUzJ3d2RrczVNRms0U1RSRVNEVm9NbTVhWDJ0TE0ydHhSSGxhVlZwVU5scHlhV3hFTTFKamJFZE5ORkJzZFVwRWNtTk1ZbHB2T0VWTFdHaE5VVUkzYTJwQ1VFWkZNbk42U2tWdWIxTmtiMEZ6UW1SclowSTRaMDAwVFdFNVVYQm1RMHBwUXpKVGJVUktSMWhpUzNCRVZrbHJWRnBQVGxsQ05sQlBUV2hsZFVwWVRIUjJaV3RzV1c5aU5EVkxVWFI1T1V4b1drWnFSUW89IgoKLS0tCmFwaVZlcnNpb246IHJiYWMuYXV0aG9yaXphdGlvbi5rOHMuaW8vdjEKa2luZDogQ2x1c3RlclJvbGUKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApydWxlczoKLSBhcGlHcm91cHM6IFsiIl0KICByZXNvdXJjZXM6IFsic2VjcmV0cyIsICJjb25maWdtYXBzIiwgInNlcnZpY2VhY2NvdW50cyJdCiAgdmVyYnM6IFsiY3JlYXRlIiwgImdldCIsICJsaXN0IiwgInVwZGF0ZSIsICJ3YXRjaCIsICJwYXRjaCIsICJkZWxldGUiXQotIGFwaUdyb3VwczogWyJhdXRob3JpemF0aW9uLms4cy5pbyJdCiAgcmVzb3VyY2VzOiBbInN1YmplY3RhY2Nlc3NyZXZpZXdzIl0KICB2ZXJiczogWyJjcmVhdGUiXQotIGFwaUdyb3VwczogWyIiXQogIHJlc291cmNlczogWyJuYW1lc3BhY2VzIl0KICB2ZXJiczogWyJjcmVhdGUiLCAiZ2V0IiwgImxpc3QiLCAid2F0Y2giLCJkZWxldGUiXQotIGFwaUdyb3VwczogWyIiXQogIHJlc291cmNlczogWyJub2RlcyJdCiAgdmVyYnM6IFsiZ2V0IiwgImxpc3QiLCAid2F0Y2giXQotIGFwaUdyb3VwczogWyIiLCAiZXZlbnRzLms4cy5pbyJdCiAgcmVzb3VyY2VzOiBbImV2ZW50cyJdCiAgdmVyYnM6IFsiY3JlYXRlIiwgInBhdGNoIiwgInVwZGF0ZSJdCi0gYXBpR3JvdXBzOiBbImFwcHMiXQogIHJlc291cmNlczogWyJkZXBsb3ltZW50cyJdCiAgdmVyYnM6IFsiY3JlYXRlIiwgImdldCIsICJsaXN0IiwgInVwZGF0ZSIsICJ3YXRjaCIsICJwYXRjaCIsICJkZWxldGUiXQotIGFwaUdyb3VwczogWyJyYmFjLmF1dGhvcml6YXRpb24uazhzLmlvIl0KICByZXNvdXJjZXM6IFsiY2x1c3RlcnJvbGViaW5kaW5ncyIsICJyb2xlYmluZGluZ3MiXQogIHZlcmJzOiBbImNyZWF0ZSIsICJnZXQiLCAibGlzdCIsICJ1cGRhdGUiLCAid2F0Y2giLCAicGF0Y2giLCAiZGVsZXRlIl0KLSBhcGlHcm91cHM6IFsicmJhYy5hdXRob3JpemF0aW9uLms4cy5pbyJdCiAgcmVzb3VyY2VzOiBbImNsdXN0ZXJyb2xlcyIsICJyb2xlcyJdCiAgdmVyYnM6IFsiY3JlYXRlIiwgImdldCIsICJsaXN0IiwgInVwZGF0ZSIsICJ3YXRjaCIsICJwYXRjaCIsICJkZWxldGUiLCAiZXNjYWxhdGUiLCAiYmluZCJdCi0gYXBpR3JvdXBzOiBbImFwaWV4dGVuc2lvbnMuazhzLmlvIl0KICByZXNvdXJjZXM6IFsiY3VzdG9tcmVzb3VyY2VkZWZpbml0aW9ucyJdCiAgdmVyYnM6IFsiY3JlYXRlIiwgImdldCIsICJsaXN0IiwgInVwZGF0ZSIsICJ3YXRjaCIsICJwYXRjaCIsICJkZWxldGUiXQotIGFwaUdyb3VwczogWyJvcGVyYXRvci5vcGVuLWNsdXN0ZXItbWFuYWdlbWVudC5pbyJdCiAgcmVzb3VyY2VzOiBbImtsdXN0ZXJsZXRzIl0KICB2ZXJiczogWyJnZXQiLCAibGlzdCIsICJ3YXRjaCIsICJ1cGRhdGUiLCAicGF0Y2giLCAiZGVsZXRlIl0KLSBhcGlHcm91cHM6IFsib3BlcmF0b3Iub3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQuaW8iXQogIHJlc291cmNlczogWyJrbHVzdGVybGV0cy9zdGF0dXMiXQogIHZlcmJzOiBbInVwZGF0ZSIsICJwYXRjaCJdCi0gYXBpR3JvdXBzOiBbIndvcmsub3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQuaW8iXQogIHJlc291cmNlczogWyJhcHBsaWVkbWFuaWZlc3R3b3JrcyJdCiAgdmVyYnM6IFsibGlzdCIsICJ1cGRhdGUiLCAicGF0Y2giXQoKLS0tCmFwaVZlcnNpb246IHJiYWMuYXV0aG9yaXphdGlvbi5rOHMuaW8vdjEKa2luZDogQ2x1c3RlclJvbGUKbWV0YWRhdGE6CiAgbmFtZTogb3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQ6a2x1c3RlcmxldC1hZG1pbi1hZ2dyZWdhdGUtY2x1c3RlcnJvbGUKICBsYWJlbHM6CiAgICByYmFjLmF1dGhvcml6YXRpb24uazhzLmlvL2FnZ3JlZ2F0ZS10by1hZG1pbjogInRydWUiCnJ1bGVzOgotIGFwaUdyb3VwczogWyJvcGVyYXRvci5vcGVuLWNsdXN0ZXItbWFuYWdlbWVudC5pbyJdCiAgcmVzb3VyY2VzOiBbImtsdXN0ZXJsZXRzIl0KICB2ZXJiczogWyJnZXQiLCAibGlzdCIsICJ3YXRjaCIsICJjcmVhdGUiLCAidXBkYXRlIiwgInBhdGNoIiwgImRlbGV0ZSJdCi0tLQphcGlWZXJzaW9uOiByYmFjLmF1dGhvcml6YXRpb24uazhzLmlvL3YxCmtpbmQ6IENsdXN0ZXJSb2xlQmluZGluZwptZXRhZGF0YToKICBuYW1lOiBrbHVzdGVybGV0CnJvbGVSZWY6CiAgYXBpR3JvdXA6IHJiYWMuYXV0aG9yaXphdGlvbi5rOHMuaW8KICBraW5kOiBDbHVzdGVyUm9sZQogIG5hbWU6IGtsdXN0ZXJsZXQKc3ViamVjdHM6Ci0ga2luZDogU2VydmljZUFjY291bnQKICBuYW1lOiBrbHVzdGVybGV0CiAgbmFtZXNwYWNlOiAib3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQtYWdlbnQiCgotLS0Ka2luZDogRGVwbG95bWVudAphcGlWZXJzaW9uOiBhcHBzL3YxCm1ldGFkYXRhOgogIG5hbWU6IGtsdXN0ZXJsZXQKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBsYWJlbHM6CiAgICBhcHA6IGtsdXN0ZXJsZXQKc3BlYzoKICByZXBsaWNhczogMQogIHNlbGVjdG9yOgogICAgbWF0Y2hMYWJlbHM6CiAgICAgIGFwcDoga2x1c3RlcmxldAogIHRlbXBsYXRlOgogICAgbWV0YWRhdGE6CiAgICAgIGFubm90YXRpb25zOgogICAgICAgIHRhcmdldC53b3JrbG9hZC5vcGVuc2hpZnQuaW8vbWFuYWdlbWVudDogJ3siZWZmZWN0IjogIlByZWZlcnJlZER1cmluZ1NjaGVkdWxpbmcifScKICAgICAgbGFiZWxzOgogICAgICAgIGFwcDoga2x1c3RlcmxldAogICAgc3BlYzoKICAgICAgc2VydmljZUFjY291bnROYW1lOiBrbHVzdGVybGV0CiAgICAgIHRvbGVyYXRpb25zOgogICAgICAgIC0gZWZmZWN0OiBOb1NjaGVkdWxlCiAgICAgICAgICBrZXk6IG5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhCiAgICAgICAgICBvcGVyYXRvcjogRXhpc3RzCiAgICAgIGNvbnRhaW5lcnM6CiAgICAgIC0gbmFtZToga2x1c3RlcmxldAogICAgICAgIGltYWdlOiByZWdpc3RyeS5yZWRoYXQuaW8vcmhhY20yL3JlZ2lzdHJhdGlvbi1yaGVsOC1vcGVyYXRvckBzaGEyNTY6OWQ5YjZkYTVjMWZiMTQ4N2YxODk1MjIyMzUxODk0ZDYxMTE4ZDA1ZWY5ZTVmNDBjMTAxMTY1YjIxYzE2Nzc5NwogICAgICAgIGltYWdlUHVsbFBvbGljeTogSWZOb3RQcmVzZW50CiAgICAgICAgYXJnczoKICAgICAgICAgIC0gIi9yZWdpc3RyYXRpb24tb3BlcmF0b3IiCiAgICAgICAgICAtICJrbHVzdGVybGV0IgogICAgICAgIGxpdmVuZXNzUHJvYmU6CiAgICAgICAgICBodHRwR2V0OgogICAgICAgICAgICBwYXRoOiAvaGVhbHRoegogICAgICAgICAgICBzY2hlbWU6IEhUVFBTCiAgICAgICAgICAgIHBvcnQ6IDg0NDMKICAgICAgICAgIGluaXRpYWxEZWxheVNlY29uZHM6IDIKICAgICAgICAgIHBlcmlvZFNlY29uZHM6IDEwCiAgICAgICAgcmVhZGluZXNzUHJvYmU6CiAgICAgICAgICBodHRwR2V0OgogICAgICAgICAgICBwYXRoOiAvaGVhbHRoegogICAgICAgICAgICBzY2hlbWU6IEhUVFBTCiAgICAgICAgICAgIHBvcnQ6IDg0NDMKICAgICAgICAgIGluaXRpYWxEZWxheVNlY29uZHM6IDIKCi0tLQphcGlWZXJzaW9uOiBvcGVyYXRvci5vcGVuLWNsdXN0ZXItbWFuYWdlbWVudC5pby92MQpraW5kOiBLbHVzdGVybGV0Cm1ldGFkYXRhOgogIG5hbWU6IGtsdXN0ZXJsZXQKc3BlYzoKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL3JoYWNtMi9yZWdpc3RyYXRpb24tcmhlbDhAc2hhMjU2OmE4N2EyNDBkNWY5ZmQ1YTk5YzJhOTJhNTg5NjEyOTU3NTkwNGU2MzkyNDgwMDRjZmI4NDQ2ZGYyNmRkYmUxZGIiCiAgd29ya0ltYWdlUHVsbFNwZWM6ICJyZWdpc3RyeS5yZWRoYXQuaW8vcmhhY20yL3dvcmstcmhlbDhAc2hhMjU2OjAxMmIwMGI3ZjE2NDQ3MzcxYjc1ZDIyZTk4Y2I5ZDk3ZTg2NWJlZDI3ZWVhODA4MzNmNDc1YmI4ODNiYWNhNWIiCiAgY2x1c3Rlck5hbWU6ICJhenVyZWNsdXN0ZXIiCiAgbmFtZXNwYWNlOiAib3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQtYWdlbnQiCiAgbm9kZVBsYWNlbWVudDoKICAgIHRvbGVyYXRpb25zOgogICAgLSBlZmZlY3Q6IE5vU2NoZWR1bGUKICAgICAga2V5OiBub2RlLXJvbGUua3ViZXJuZXRlcy5pby9pbmZyYQogICAgICBvcGVyYXRvcjogRXhpc3RzCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
customresourcedefinition.apiextensions.k8s.io/klusterlets.operator.open-cluster-management.io created
namespace/open-cluster-management-agent created
serviceaccount/klusterlet created
secret/bootstrap-hub-kubeconfig created
clusterrole.rbac.authorization.k8s.io/klusterlet created
clusterrole.rbac.authorization.k8s.io/open-cluster-management:klusterlet-admin-aggregate-clusterrole created
clusterrolebinding.rbac.authorization.k8s.io/klusterlet created
Warning: would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "klusterlet" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "klusterlet" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "klusterlet" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "klusterlet" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/klusterlet created
klusterlet.operator.open-cluster-management.io/klusterlet created
rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
SFdsRlNiVVo2V2xSVk0xUlVRa1pYUldoTldtdEdNRkpIZUc1U2JWcFNUVWhPY21GNmEzaE1NMnhRV2tkek1VMVRPVkJXVkZsMlZGUmtka051Vm5CV1ZteHBVMFJDUlZsclozWlNibWhFVld4V2VsbFZjRlJMTUVwc1UzazVWRlJxU2pOVVIxcHJaRVJzTW1KR2FHdGlNSGN3VjFWR2JtVkVSbTVPUjNoaFVXbHpNVkpXWkdGVU0xWlVXVlJhTkZKWVFVdGpNMFUxWW14bmRsZHNUa2xQUkVaRVdXdFdXbEo2YkVWUFNHUnpZbTVzVVZKRlpIVk9helZXVTBWd1UxTnJaSFpoUjBwRFpFWlpjbUY2YUVkYWVqQTVRMmt3ZEV4VE1IUlNWVFZGU1VWT1JsVnNVa3BTYTJ4RVVWWlNSa3hUTUhSTVV6QkxURk13ZEV4VE1VTlNWV1JLVkdsQ1JGSldTbFZUVlZwS1VUQkdWVkpUTUhSTVV6QjBRMnN4U2xOVldrZGhhMDVFVVZoWk1sb3dSak5UVlVwQ1dqQnNVMUZWY0VaamEwNUdZMnhDUlZGdGJIVldVemxwVmpCNGNGWXlOVmxOVnprelVrWkdXbE5yZEhaWGEyeHZaRzFPVDFGV1JrWlVSVXBTVVZoalMxWkljRVpVUlRGQ1lUQmtRazFXVmtaUmJXaE9VVEZhVjFSWWFFeFdSVVoxVVcxa1QxWnJTa0ppTVZKS1VsZDRNVnBGWkZkbFYwcDBWbXBDU2xKck5YTlhWRTVYWlZkR1dWVnFWa3BTYTNCeldYcEtWMkZCY0dwaVZUVjJVMVZXYTJWWFNYcFdibVJPVld4V00xSllaRnBTUmxwU1ZWVlNSbVF6YUV0V1ZFWkxVMFZzUjFOdVdtbE5NVVp1VmpCU1JtUXdhRzlaTURWT1lXdEdNMVF4VWtKTlJURkZVVmhrVGxKRlJqTkRiR1J2V1RBMVRtRnNWak5VTVZKR1RWVXhWVmRZWkU1U1JVWXpWakp3UW1WVk1WSmpNMlJFVlZac1JWWnNSbEpTTUZZelUyeGFWbVZyVmxoVVZVcFNVakJGZUZaVlZrUmhSVEZQVmtWa1YwMUZiM3BVVjJOTFZXeGpNV0Z0VG5WaVNHUnJVa1ZXVFZSVlJuSlNNRVY0VmxWV1FtVkZNVVJXVjNCT1pESmtibEpYYkU1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRldSbFpSVlVVd1UxVktSV1F3UmpOYU1tUkdVM2R3UW1Jd2JFTlJWa1pFVGpCR2IxWlhPVFpWUjBadVlrVTFUbFZGVmpGbFZUVlhWMnQ0UlVzd2JFMWxSekZvVjJwYVVtSXliSFZYUms1b1kxaFNWR1JVVmpSV1dHdzBZMnBSTVdOcGRGbFhSV3gyVDFkT1VVTnNTVEZWVmxaWFZrWmFXV0ZyYnpKaU1qbHhZVEZ2TlZkVmF6UlZXRVp6VkRKS01sWlVaRE5sVkdScFlXMU9SR1F4YUZGVWJIQlFWREphTUdWcVNuVmtNV1J1WXpKS01tTXdUbFpUYTA1WVUwTjBjVnBJWjB0ak0yaFJZbXRvVEdWdGFIUkxlVGxwVGxWU01GSnNWbkpXTVdSNFdUQmFWV1Z0Y0ZWVFZsWXhUbXBHZVdSVVNsRk5NakZEWkhwU2VGWnNWbmhPTVhBd1VraENiR0pHUmtWVmJrcE1UMVU0TkZkdVZqQmlVWEJQVTBodk1sbFVVakZWUmxvMVlsWnZjbEpGUmxsWFIwcDNaVmRKZG1SVlNqUlpWRTVVWVVkNGJrOVZXVFJhYlRWRVdXNWFORk41T1d4U2VrNU9VMGRHYWxacVRsWlZibFpSVkZoS1ZGZEZTbkJVU0dodVEyeHZlbFp0TVhwTU1GWmFUMVJhUzFsNlZuTlZRemxRWWpKcmVWVnFXbGxNTUZZMFlXNUdkRkZYZDNwVlJGVjRWa04wYWs5RlNURmFiR1IwV1RCS2FsWllTWGxVTW5OMlRsY3hObUY2VlhwWk1WVXlXVEJqUzB3eWRIQlNhMmhvVW01Q2VXRldXWGhrV0doUlZGWldibFZFUlROV2EyUnZZVlJzZWxaclJtNVVWVXBDVVZWa2NWb3laRVpUVlRGS1UxVktRMUpGUmxCUmJXUlBWbXRvVWs5RlNrSmFhbWhHVVd0R1RsRjNjRUpYVm13elUwWkdXbEpHV2xOTlIzaERVV3hzTTFKclJscFRWWFF6VjFWS1ExVldWa2xSV0dSS1VqQk9SR013WkVKVlZsWkhVVzVrVGxGck1VTlRWV1JDVFZaV2ExSllaRVpSYVRrelZWVnNUbEZXYkVORGEwWnRUMFZPUWxWVlJqTlRSa1phVWtaYVUwMUZPVU5SYkd4R1VtdEtVbVJZVGpSYVZFNVlVbTFLVFdOdGVFSlRiRVpRVjFkYWVVNVVTazFTYXpGTlVqQXhRMDlGWkVKTlZsWnJVMWhrVWxkVk1VTlpWVVZMVW10b2RFMUdaR3hYYW1Rd1pGWm9jbEZXYUZCUlZVNUtZV3RzU0dKSGIzbE9iSEF3WkZVeFJWTlZaRVJSTTA1SVVWWkdWbEpyU2pOU1ZVcERVVEZzTTFOclVrSmhWVXB1V2pOS1Exb3dWa2RSYkVacVpIZHdRbUl4YkZoWlZXaFRUVWRPUldJeldrMU5NbVEwVkVjeGNtUlhTa2hXYmxaYVRUQnNNVmxxVGt0aWEzZzJVVmMxUTFvd05WZFRSa2swVWxWc1JWRlhWazVSYm14dVVqTkdRbGRYYUc5WGJUbHJVMFpLTTBOck9YQlBTRnBzVWtWV01WZFlhekZqTVhCWVRsZHdhbUZVVmpKWk1qRnFaR3N4UkZOVlpFSk5WbFpyVTFWR1VsbHJNVU5oTTJSRVVWWnNTRmRxVWtaVVZVWlNVMVZLVGxGVVFraFJNMng2VWpCR1VsVlZTVXRhTTFFMFZrVkdVbEpWU2s1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRXpaRlpSVlVVd1UxVk9RbFZWVGtkbFYzTXhVMFpDZUZWRVRtOVdWazVIWkdzMVYySnRWazFUTVd4YVRtcEZlRlpHU1RKV2QzQlJWa1UxYzFreWVGSmtSMlJvVWtoR00wdDZUVEJUVlhjMVdtNXdUVnBJWkVKVVIxSXhWSGs1WVZwWGVFOU9NblJLVTJsMGRFNTZVakZsVlVWeVdsZHNNRlZzYXpSaE1rMHlUVVJrVldFd1RURk5NMlJ6UTIxc2NscHRNV0ZXZWxGMlZXNWFWVmRxYUU1T2JGWk1TM3BXVm1WdGFFeFBSM0JFV2tWNE1WUlZaRnBVUkZwTVpHNXdXVkl4U2xSYU1tdDZaVlY0Ym1GdFZqTlZXRkpFVlVkMFNsWnViekpTUkVwU1ZWaHZTMUV5ZEdwaFIxWkNZbFZPUzA5Rk1YaGxWWEF4VGxod2MyVnViR0ZVVjNCQ1pHMDFkVkZXVVRCT1dGSlRVVmhvYkdFelNucGtWR3N3WXpGRk1GcFhaR3RWYTA1MVdXeGtWRkpJVWxwT01uUnZTekJLU21KUmNITlRhelZaWWpCSmVHSkZTazVTVlhSS1kxUlNVbEpHVmxCWFJ6bFRXakphYldSVlVtNWhSM0JzVFZaa2VWSjZiRTVVUTNSSldXMXNlbU5UT1RWU2F6bElaREZvUlU5V1NuQlhSR2hIVG01T00wNXNZekJEYlVZeVVWaFdNbEpJVGpaa1YxVXhWRVJPZW1WcVp6RlRlWFJHVVhwU1drd3paRWRXYTFKUFpHeHdkazVHVWxwWFIwWjJUbXh2ZDFwcGRITlZWWFJxVFVoUk5GSkdSbHBsYlhONFZERm9WMlJVYUhsalJFbExaVlZ3VGxGNldtaGlSWGhwVVcxYVVGSkZSazFYYmxwYVUwUmtkVTR5VW5aTlZVWmhZa2hOTUZOVWJHdE5Wa0V3WVcwMWNsSklTbEppTTJoRFRURldlRlZVYkc5V2JYZDZWRVZXVEZWVVkzcGxSVmw0Vkhkd05WTjZWa2hoUlZKRlYwUm9kbFp0V2toVE1Ga3haRk4wYTFwWFRrcGpNR2N3VjFkR1ZXUjZaSFJWUkU1SVVtNW9TMVV6UmpKTmVYTjNZa1pXUjFOdE9YQk9WWGhxVGxkU2FFMVVVVFZqUkd0M1UxZFNla050YUVSU1dHaDVZakIzZUV0NlpIUmpibXhLWVRGb1VWcFZXazVPVmxKdVZIcHNlVTFJU2pKWGJVWkRVbXM1TWxacVNqWk5SMlIzVFhwV1lVMURkRTFPUm1SUllrZEtNVkpYY0U5TU1uZzBWVVZhY0dKcGMwdFRSM2hXWVc1Sk5Gb3hTbnBUVkU1NFdtdHdVRlZWV2pWTWVteDVVekJzUzFWcVFscE1lbWhRWWxoa01FeDZhSFpXUm1SdVpWUkdkRnBIVmtsaVZ6RnhZWHBrY1UxWE5WcGpNMXBFVDFWd1ZGVlVXbUZrWjNCT1lrZFNjMVpHVWt4UmFrNDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTA1ZDJoNE5TNDVkMmg0TlM1ellXNWtZbTk0TVRRd015NXZjR1Z1ZEd4akxtTnZiVG8yTkRRekNpQWdibUZ0WlRvZ1pHVm1ZWFZzZEMxamJIVnpkR1Z5Q21OdmJuUmxlSFJ6T2dvdElHTnZiblJsZUhRNkNpQWdJQ0JqYkhWemRHVnlPaUJrWldaaGRXeDBMV05zZFhOMFpYSUtJQ0FnSUc1aGJXVnpjR0ZqWlRvZ1pHVm1ZWFZzZEFvZ0lDQWdkWE5sY2pvZ1pHVm1ZWFZzZEMxaGRYUm9DaUFnYm1GdFpUb2daR1ZtWVhWc2RDMWpiMjUwWlhoMENtTjFjbkpsYm5RdFkyOXVkR1Y0ZERvZ1pHVm1ZWFZzZEMxamIyNTBaWGgwQ210cGJtUTZJRU52Ym1acFp3cHdjbVZtWlhKbGJtTmxjem9nZTMwS2RYTmxjbk02Q2kwZ2JtRnRaVG9nWkdWbVlYVnNkQzFoZFhSb0NpQWdkWE5sY2pvS0lDQWdJSFJ2YTJWdU9pQmxlVXBvWWtkamFVOXBTbE5WZWtreFRtbEpjMGx0ZEhCYVEwazJTVzVrVUdJd1dtaFZWVTV1VDFWWk0wNVdWbXhTV0VwWVkydEdWbU5zUmpKWWVtUkVWa2hzVm1SWFJtcFdWVkpZVXpKR2RWb3dNVEJTVjAxcFpsRXVaWGxLY0dNelRXbFBhVXB5WkZkS2JHTnROV3hrUjFaNlRETk9iR051V25CWk1sWm9XVEpPZG1SWE5UQkphWGRwWVROV2FWcFlTblZhV0ZKc1kzazFjR0o1T1hwYVdFb3lZVmRPYkZsWFRtcGlNMVoxWkVNNWRWbFhNV3hqTTBKb1dUSlZhVTlwU21obGJsWjVXbGRPYzJSWVRqQmFXRWxwVEVOS2NtUlhTbXhqYlRWc1pFZFdla3h0YkhaTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1Fd3pUbXhaTTBwc1pFTTFkVmxYTVd4SmFtOXBXVmh3TVdOdFZtcGlTRlo2WkVkV2VVeFhTblppTTFKNlpFaEthR05ETVhwWlV6RXdZakowYkdKcE1YaGpibEowWkdsSmMwbHRkREZaYlZaNVltMVdNRnBZVFhWaFZ6aDJZekpXZVdSdGJHcGFWMFpxV1RJNU1XSnVVWFpqTWxaNVpHMXNhbHBUTVdoWk1rNTJaRmMxTUV4dE5XaGlWMVZwVDJsS2FHVnVWbmxhVjA1elpGaE9NRnBZU1hSWmJUbDJaRWhPTUdOdFJuZE1XRTVvU1dsM2FXRXpWbWxhV0VwMVdsaFNiR041TlhCaWVUbDZXbGhLTW1GWFRteFpWMDVxWWpOV2RXUkRPWHBhV0VveVlWZE9iRXhYUm1wWk1qa3hZbTVSZFdSWGJHdEphbTlwV1ZkUmVrOUhWVEphUkdOMFdUSlZOVTFETURCUFJFVXhURlJuTWsxWFRYUk9iVkpzV20xVk1rMXFZekZOUjFFd1NXbDNhV016Vm1sSmFtOXBZek5zZW1SSFZuUlBiazVzWTI1YWNGa3lWbWhaTWs1MlpGYzFNRTl0Umpaa1dFcHNXVEo0TVdNelVteGphbkJvWlc1V2VWcFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaEpiakF1Y0U1V05qY3lWbk50WkhKNVREUjViVkpUYlROR2FIRTBhbmhaTjNWVWJFRkdhWE5SWmpGalpYUXdiVTl4VG14SE9XbFRjRTlmVW5kbldXVjRkbEpWVmtodlEyZzRNSGcxZFVKaWVYTmhOMDVmZVZaQk9XTkVVa3hFVWpoSVZISkxkMXBtU0VkbFdGOUpiMk5UUm5wWE9VWnFVRmRDZWtabFdHODNOSEZrYmpRMFQwUnRZWEp5YzNsWU5EbEVaamRPZFhnNGQyUmlUelZ3TFdod2NFc3hNVTl1U3pWS2RrMXNWV0Z6T0ZCMWRVbDBUV2xOYTBOaFVtNTJWakZTVjB0b1dWUm9NRWR1Y25CYWRVbFNWRXhhVmw5c1ozcGtZM0JMVFMxamNuVTVZVEEzUzFkdk0wbHphRVF5V0V0VWF6QXlOSGcxVEZsd2FWcEVhRk5ZWlZkblYzSjJNSFV4ZURWc2EySTBhalZyU1VVNE5ERTVNMVJaT0ZKNWRVZzJSMnBPTFd0UlVVYzRlVTlLTWkxM1RWcGpUVkpVVDE5UWVuTk5TSEl6WjFNemEwTk1SRmMzTFV4SFMwaHRTR2RVVjFGeGRXbzFPSEE0VkY5QlJUaFFUelpJTW5NMmNVOUZaR2xQVnpoSVJHTlFMUzB0YjFaa09FMTZhMVZ1VjA1RGExRk5UeTFuUWtsS1p6QmFNVmh1VkhkZmVHZFJabGRRUzNSVVkyMU1RM2RMVEcxcllWTTFOVkJ5V1VwUlpsWm9kMjh5UlhST1dYVkJjWFl5ZVhaUGExZElja2hRVkhsV01UaENTVnAwV2t4elQyMTVVRjgzTW5BM2FqZDVkM05CZGpSb1pHdHVXVmt4ZUVOeVoybHFNWFp4YVVnNFkyYzFkVFpaY0VsaWJUWjRaa0ZDV0dwekxVNXphbDltU1RseFZ6aFlXRGRLVFdWMlUyOTZRbGd3TkZsVVkwRnZkemRWZVdkbWMycDRaemg2WW1sV01FZzFha2QzWjBGdGEyWjRWR3BDWDFkcVVWQllTVll4ZVcxbll5MU9UVXRmV1hoWlpVUlJjWFpCVFY5eE5YUmlkRWRNZHpkc1JreFliamgwT0RsdWNXTlZTa1JYTFdnNWQwa3RjVEZ1VG5kWGFuWXhhamhIT1V4elpsSTNWemg2WkZGeGFUZ3dSQzA1Umt0TmQyc3RjamxYUVhGR2VHaHNSbEVLIgoKLS0tCmFwaVZlcnNpb246IG9wZXJhdG9yLm9wZW4tY2x1c3Rlci1tYW5hZ2VtZW50LmlvL3YxCmtpbmQ6IEtsdXN0ZXJsZXQKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApzcGVjOgogIGRlcGxveU9wdGlvbjoKICAgIG1vZGU6IERlZmF1bHQKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvcmVnaXN0cmF0aW9uLXJoZWw4QHNoYTI1NjpiY2M2ZDEyYmE0ZjFkY2Q3ZmEwMDg2M2YyODhlZDhiYzkxM2M2NjViYWNlYmFjNzliMzYwODgwZDFjZTMzMDUwIgogIHdvcmtJbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvd29yay1yaGVsOEBzaGEyNTY6YTJmYmI0ZmFiMDA3MzU2M2I4ZWQyODk1ODU5Y2Q4YjcwNTgzNTM0MTk0YTYyMjI4NzExZTBjMzc4YTk1NjU5MiIKICBjbHVzdGVyTmFtZTogImF6dXJlY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
I0718 11:28:41.607340   54230 request.go:668] Waited for 1.001052305s due to client-side throttling, not priority and fairness, request: GET:https://api.ocp4-c6d5q-ipi.azure.opentlc.com:6443/apis/network.openshift.io/v1?timeout=32s
Error from server (AlreadyExists): error when creating "STDIN": customresourcedefinitions.apiextensions.k8s.io "klusterlets.operator.open-cluster-management.io" already exists
The cluster cannot be imported because its Klusterlet CRD already exists.
Either the cluster was already imported, or it was not detached completely during a previous detach process.
Detach the existing cluster before trying the import again.%                                                                                                                                                                                                                                        rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
SFdsRlNiVVo2V2xSVk0xUlVRa1pYUldoTldtdEdNRkpIZUc1U2JWcFNUVWhPY21GNmEzaE1NMnhRV2tkek1VMVRPVkJXVkZsMlZGUmtka051Vm5CV1ZteHBVMFJDUlZsclozWlNibWhFVld4V2VsbFZjRlJMTUVwc1UzazVWRlJxU2pOVVIxcHJaRVJzTW1KR2FHdGlNSGN3VjFWR2JtVkVSbTVPUjNoaFVXbHpNVkpXWkdGVU0xWlVXVlJhTkZKWVFVdGpNMFUxWW14bmRsZHNUa2xQUkVaRVdXdFdXbEo2YkVWUFNHUnpZbTVzVVZKRlpIVk9helZXVTBWd1UxTnJaSFpoUjBwRFpFWlpjbUY2YUVkYWVqQTVRMmt3ZEV4VE1IUlNWVFZGU1VWT1JsVnNVa3BTYTJ4RVVWWlNSa3hUTUhSTVV6QkxURk13ZEV4VE1VTlNWV1JLVkdsQ1JGSldTbFZUVlZwS1VUQkdWVkpUTUhSTVV6QjBRMnN4U2xOVldrZGhhMDVFVVZoWk1sb3dSak5UVlVwQ1dqQnNVMUZWY0VaamEwNUdZMnhDUlZGdGJIVldVemxwVmpCNGNGWXlOVmxOVnprelVrWkdXbE5yZEhaWGEyeHZaRzFPVDFGV1JrWlVSVXBTVVZoalMxWkljRVpVUlRGQ1lUQmtRazFXVmtaUmJXaE9VVEZhVjFSWWFFeFdSVVoxVVcxa1QxWnJTa0ppTVZKS1VsZDRNVnBGWkZkbFYwcDBWbXBDU2xKck5YTlhWRTVYWlZkR1dWVnFWa3BTYTNCeldYcEtWMkZCY0dwaVZUVjJVMVZXYTJWWFNYcFdibVJPVld4V00xSllaRnBTUmxwU1ZWVlNSbVF6YUV0V1ZFWkxVMFZzUjFOdVdtbE5NVVp1VmpCU1JtUXdhRzlaTURWT1lXdEdNMVF4VWtKTlJURkZVVmhrVGxKRlJqTkRiR1J2V1RBMVRtRnNWak5VTVZKR1RWVXhWVmRZWkU1U1JVWXpWakp3UW1WVk1WSmpNMlJFVlZac1JWWnNSbEpTTUZZelUyeGFWbVZyVmxoVVZVcFNVakJGZUZaVlZrUmhSVEZQVmtWa1YwMUZiM3BVVjJOTFZXeGpNV0Z0VG5WaVNHUnJVa1ZXVFZSVlJuSlNNRVY0VmxWV1FtVkZNVVJXVjNCT1pESmtibEpYYkU1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRldSbFpSVlVVd1UxVktSV1F3UmpOYU1tUkdVM2R3UW1Jd2JFTlJWa1pFVGpCR2IxWlhPVFpWUjBadVlrVTFUbFZGVmpGbFZUVlhWMnQ0UlVzd2JFMWxSekZvVjJwYVVtSXliSFZYUms1b1kxaFNWR1JVVmpSV1dHdzBZMnBSTVdOcGRGbFhSV3gyVDFkT1VVTnNTVEZWVmxaWFZrWmFXV0ZyYnpKaU1qbHhZVEZ2TlZkVmF6UlZXRVp6VkRKS01sWlVaRE5sVkdScFlXMU9SR1F4YUZGVWJIQlFWREphTUdWcVNuVmtNV1J1WXpKS01tTXdUbFpUYTA1WVUwTjBjVnBJWjB0ak0yaFJZbXRvVEdWdGFIUkxlVGxwVGxWU01GSnNWbkpXTVdSNFdUQmFWV1Z0Y0ZWVFZsWXhUbXBHZVdSVVNsRk5NakZEWkhwU2VGWnNWbmhPTVhBd1VraENiR0pHUmtWVmJrcE1UMVU0TkZkdVZqQmlVWEJQVTBodk1sbFVVakZWUmxvMVlsWnZjbEpGUmxsWFIwcDNaVmRKZG1SVlNqUlpWRTVVWVVkNGJrOVZXVFJhYlRWRVdXNWFORk41T1d4U2VrNU9VMGRHYWxacVRsWlZibFpSVkZoS1ZGZEZTbkJVU0dodVEyeHZlbFp0TVhwTU1GWmFUMVJhUzFsNlZuTlZRemxRWWpKcmVWVnFXbGxNTUZZMFlXNUdkRkZYZDNwVlJGVjRWa04wYWs5RlNURmFiR1IwV1RCS2FsWllTWGxVTW5OMlRsY3hObUY2VlhwWk1WVXlXVEJqUzB3eWRIQlNhMmhvVW01Q2VXRldXWGhrV0doUlZGWldibFZFUlROV2EyUnZZVlJzZWxaclJtNVVWVXBDVVZWa2NWb3laRVpUVlRGS1UxVktRMUpGUmxCUmJXUlBWbXRvVWs5RlNrSmFhbWhHVVd0R1RsRjNjRUpYVm13elUwWkdXbEpHV2xOTlIzaERVV3hzTTFKclJscFRWWFF6VjFWS1ExVldWa2xSV0dSS1VqQk9SR013WkVKVlZsWkhVVzVrVGxGck1VTlRWV1JDVFZaV2ExSllaRVpSYVRrelZWVnNUbEZXYkVORGEwWnRUMFZPUWxWVlJqTlRSa1phVWtaYVUwMUZPVU5SYkd4R1VtdEtVbVJZVGpSYVZFNVlVbTFLVFdOdGVFSlRiRVpRVjFkYWVVNVVTazFTYXpGTlVqQXhRMDlGWkVKTlZsWnJVMWhrVWxkVk1VTlpWVVZMVW10b2RFMUdaR3hYYW1Rd1pGWm9jbEZXYUZCUlZVNUtZV3RzU0dKSGIzbE9iSEF3WkZVeFJWTlZaRVJSTTA1SVVWWkdWbEpyU2pOU1ZVcERVVEZzTTFOclVrSmhWVXB1V2pOS1Exb3dWa2RSYkVacVpIZHdRbUl4YkZoWlZXaFRUVWRPUldJeldrMU5NbVEwVkVjeGNtUlhTa2hXYmxaYVRUQnNNVmxxVGt0aWEzZzJVVmMxUTFvd05WZFRSa2swVWxWc1JWRlhWazVSYm14dVVqTkdRbGRYYUc5WGJUbHJVMFpLTTBOck9YQlBTRnBzVWtWV01WZFlhekZqTVhCWVRsZHdhbUZVVmpKWk1qRnFaR3N4UkZOVlpFSk5WbFpyVTFWR1VsbHJNVU5oTTJSRVVWWnNTRmRxVWtaVVZVWlNVMVZLVGxGVVFraFJNMng2VWpCR1VsVlZTVXRhTTFFMFZrVkdVbEpWU2s1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRXpaRlpSVlVVd1UxVk9RbFZWVGtkbFYzTXhVMFpDZUZWRVRtOVdWazVIWkdzMVYySnRWazFUTVd4YVRtcEZlRlpHU1RKV2QzQlJWa1UxYzFreWVGSmtSMlJvVWtoR00wdDZUVEJUVlhjMVdtNXdUVnBJWkVKVVIxSXhWSGs1WVZwWGVFOU9NblJLVTJsMGRFNTZVakZsVlVWeVdsZHNNRlZzYXpSaE1rMHlUVVJrVldFd1RURk5NMlJ6UTIxc2NscHRNV0ZXZWxGMlZXNWFWVmRxYUU1T2JGWk1TM3BXVm1WdGFFeFBSM0JFV2tWNE1WUlZaRnBVUkZwTVpHNXdXVkl4U2xSYU1tdDZaVlY0Ym1GdFZqTlZXRkpFVlVkMFNsWnViekpTUkVwU1ZWaHZTMUV5ZEdwaFIxWkNZbFZPUzA5Rk1YaGxWWEF4VGxod2MyVnViR0ZVVjNCQ1pHMDFkVkZXVVRCT1dGSlRVVmhvYkdFelNucGtWR3N3WXpGRk1GcFhaR3RWYTA1MVdXeGtWRkpJVWxwT01uUnZTekJLU21KUmNITlRhelZaWWpCSmVHSkZTazVTVlhSS1kxUlNVbEpHVmxCWFJ6bFRXakphYldSVlVtNWhSM0JzVFZaa2VWSjZiRTVVUTNSSldXMXNlbU5UT1RWU2F6bElaREZvUlU5V1NuQlhSR2hIVG01T00wNXNZekJEYlVZeVVWaFdNbEpJVGpaa1YxVXhWRVJPZW1WcVp6RlRlWFJHVVhwU1drd3paRWRXYTFKUFpHeHdkazVHVWxwWFIwWjJUbXh2ZDFwcGRITlZWWFJxVFVoUk5GSkdSbHBsYlhONFZERm9WMlJVYUhsalJFbExaVlZ3VGxGNldtaGlSWGhwVVcxYVVGSkZSazFYYmxwYVUwUmtkVTR5VW5aTlZVWmhZa2hOTUZOVWJHdE5Wa0V3WVcwMWNsSklTbEppTTJoRFRURldlRlZVYkc5V2JYZDZWRVZXVEZWVVkzcGxSVmw0Vkhkd05WTjZWa2hoUlZKRlYwUm9kbFp0V2toVE1Ga3haRk4wYTFwWFRrcGpNR2N3VjFkR1ZXUjZaSFJWUkU1SVVtNW9TMVV6UmpKTmVYTjNZa1pXUjFOdE9YQk9WWGhxVGxkU2FFMVVVVFZqUkd0M1UxZFNla050YUVSU1dHaDVZakIzZUV0NlpIUmpibXhLWVRGb1VWcFZXazVPVmxKdVZIcHNlVTFJU2pKWGJVWkRVbXM1TWxacVNqWk5SMlIzVFhwV1lVMURkRTFPUm1SUllrZEtNVkpYY0U5TU1uZzBWVVZhY0dKcGMwdFRSM2hXWVc1Sk5Gb3hTbnBUVkU1NFdtdHdVRlZWV2pWTWVteDVVekJzUzFWcVFscE1lbWhRWWxoa01FeDZhSFpXUm1SdVpWUkdkRnBIVmtsaVZ6RnhZWHBrY1UxWE5WcGpNMXBFVDFWd1ZGVlVXbUZrWjNCT1lrZFNjMVpHVWt4UmFrNDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTA1ZDJoNE5TNDVkMmg0TlM1ellXNWtZbTk0TVRRd015NXZjR1Z1ZEd4akxtTnZiVG8yTkRRekNpQWdibUZ0WlRvZ1pHVm1ZWFZzZEMxamJIVnpkR1Z5Q21OdmJuUmxlSFJ6T2dvdElHTnZiblJsZUhRNkNpQWdJQ0JqYkhWemRHVnlPaUJrWldaaGRXeDBMV05zZFhOMFpYSUtJQ0FnSUc1aGJXVnpjR0ZqWlRvZ1pHVm1ZWFZzZEFvZ0lDQWdkWE5sY2pvZ1pHVm1ZWFZzZEMxaGRYUm9DaUFnYm1GdFpUb2daR1ZtWVhWc2RDMWpiMjUwWlhoMENtTjFjbkpsYm5RdFkyOXVkR1Y0ZERvZ1pHVm1ZWFZzZEMxamIyNTBaWGgwQ210cGJtUTZJRU52Ym1acFp3cHdjbVZtWlhKbGJtTmxjem9nZTMwS2RYTmxjbk02Q2kwZ2JtRnRaVG9nWkdWbVlYVnNkQzFoZFhSb0NpQWdkWE5sY2pvS0lDQWdJSFJ2YTJWdU9pQmxlVXBvWWtkamFVOXBTbE5WZWtreFRtbEpjMGx0ZEhCYVEwazJTVzVrVUdJd1dtaFZWVTV1VDFWWk0wNVdWbXhTV0VwWVkydEdWbU5zUmpKWWVtUkVWa2hzVm1SWFJtcFdWVkpZVXpKR2RWb3dNVEJTVjAxcFpsRXVaWGxLY0dNelRXbFBhVXB5WkZkS2JHTnROV3hrUjFaNlRETk9iR051V25CWk1sWm9XVEpPZG1SWE5UQkphWGRwWVROV2FWcFlTblZhV0ZKc1kzazFjR0o1T1hwYVdFb3lZVmRPYkZsWFRtcGlNMVoxWkVNNWRWbFhNV3hqTTBKb1dUSlZhVTlwU21obGJsWjVXbGRPYzJSWVRqQmFXRWxwVEVOS2NtUlhTbXhqYlRWc1pFZFdla3h0YkhaTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1Fd3pUbXhaTTBwc1pFTTFkVmxYTVd4SmFtOXBXVmh3TVdOdFZtcGlTRlo2WkVkV2VVeFhTblppTTFKNlpFaEthR05ETVhwWlV6RXdZakowYkdKcE1YaGpibEowWkdsSmMwbHRkREZaYlZaNVltMVdNRnBZVFhWaFZ6aDJZekpXZVdSdGJHcGFWMFpxV1RJNU1XSnVVWFpqTWxaNVpHMXNhbHBUTVdoWk1rNTJaRmMxTUV4dE5XaGlWMVZwVDJsS2FHVnVWbmxhVjA1elpGaE9NRnBZU1hSWmJUbDJaRWhPTUdOdFJuZE1XRTVvU1dsM2FXRXpWbWxhV0VwMVdsaFNiR041TlhCaWVUbDZXbGhLTW1GWFRteFpWMDVxWWpOV2RXUkRPWHBhV0VveVlWZE9iRXhYUm1wWk1qa3hZbTVSZFdSWGJHdEphbTlwV1ZkUmVrOUhWVEphUkdOMFdUSlZOVTFETURCUFJFVXhURlJuTWsxWFRYUk9iVkpzV20xVk1rMXFZekZOUjFFd1NXbDNhV016Vm1sSmFtOXBZek5zZW1SSFZuUlBiazVzWTI1YWNGa3lWbWhaTWs1MlpGYzFNRTl0Umpaa1dFcHNXVEo0TVdNelVteGphbkJvWlc1V2VWcFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaEpiakF1Y0U1V05qY3lWbk50WkhKNVREUjViVkpUYlROR2FIRTBhbmhaTjNWVWJFRkdhWE5SWmpGalpYUXdiVTl4VG14SE9XbFRjRTlmVW5kbldXVjRkbEpWVmtodlEyZzRNSGcxZFVKaWVYTmhOMDVmZVZaQk9XTkVVa3hFVWpoSVZISkxkMXBtU0VkbFdGOUpiMk5UUm5wWE9VWnFVRmRDZWtabFdHODNOSEZrYmpRMFQwUnRZWEp5YzNsWU5EbEVaamRPZFhnNGQyUmlUelZ3TFdod2NFc3hNVTl1U3pWS2RrMXNWV0Z6T0ZCMWRVbDBUV2xOYTBOaFVtNTJWakZTVjB0b1dWUm9NRWR1Y25CYWRVbFNWRXhhVmw5c1ozcGtZM0JMVFMxamNuVTVZVEEzUzFkdk0wbHphRVF5V0V0VWF6QXlOSGcxVEZsd2FWcEVhRk5ZWlZkblYzSjJNSFV4ZURWc2EySTBhalZyU1VVNE5ERTVNMVJaT0ZKNWRVZzJSMnBPTFd0UlVVYzRlVTlLTWkxM1RWcGpUVkpVVDE5UWVuTk5TSEl6WjFNemEwTk1SRmMzTFV4SFMwaHRTR2RVVjFGeGRXbzFPSEE0VkY5QlJUaFFUelpJTW5NMmNVOUZaR2xQVnpoSVJHTlFMUzB0YjFaa09FMTZhMVZ1VjA1RGExRk5UeTFuUWtsS1p6QmFNVmh1VkhkZmVHZFJabGRRUzNSVVkyMU1RM2RMVEcxcllWTTFOVkJ5V1VwUlpsWm9kMjh5UlhST1dYVkJjWFl5ZVhaUGExZElja2hRVkhsV01UaENTVnAwV2t4elQyMTVVRjgzTW5BM2FqZDVkM05CZGpSb1pHdHVXVmt4ZUVOeVoybHFNWFp4YVVnNFkyYzFkVFpaY0VsaWJUWjRaa0ZDV0dwekxVNXphbDltU1RseFZ6aFlXRGRLVFdWMlUyOTZRbGd3TkZsVVkwRnZkemRWZVdkbWMycDRaemg2WW1sV01FZzFha2QzWjBGdGEyWjRWR3BDWDFkcVVWQllTVll4ZVcxbll5MU9UVXRmV1hoWlpVUlJjWFpCVFY5eE5YUmlkRWRNZHpkc1JreFliamgwT0RsdWNXTlZTa1JYTFdnNWQwa3RjVEZ1VG5kWGFuWXhhamhIT1V4elpsSTNWemg2WkZGeGFUZ3dSQzA1Umt0TmQyc3RjamxYUVhGR2VHaHNSbEVLIgoKLS0tCmFwaVZlcnNpb246IG9wZXJhdG9yLm9wZW4tY2x1c3Rlci1tYW5hZ2VtZW50LmlvL3YxCmtpbmQ6IEtsdXN0ZXJsZXQKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApzcGVjOgogIGRlcGxveU9wdGlvbjoKICAgIG1vZGU6IERlZmF1bHQKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvcmVnaXN0cmF0aW9uLXJoZWw4QHNoYTI1NjpiY2M2ZDEyYmE0ZjFkY2Q3ZmEwMDg2M2YyODhlZDhiYzkxM2M2NjViYWNlYmFjNzliMzYwODgwZDFjZTMzMDUwIgogIHdvcmtJbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvd29yay1yaGVsOEBzaGEyNTY6YTJmYmI0ZmFiMDA3MzU2M2I4ZWQyODk1ODU5Y2Q4YjcwNTgzNTM0MTk0YTYyMjI4NzExZTBjMzc4YTk1NjU5MiIKICBjbHVzdGVyTmFtZTogImF6dXJlY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
customresourcedefinition.apiextensions.k8s.io/klusterlets.operator.open-cluster-management.io created
Warning: Detected changes to resource open-cluster-management-agent which is currently being deleted.
namespace/open-cluster-management-agent unchanged
clusterrole.rbac.authorization.k8s.io/klusterlet configured
clusterrole.rbac.authorization.k8s.io/klusterlet-bootstrap-kubeconfig created
clusterrole.rbac.authorization.k8s.io/open-cluster-management:klusterlet-admin-aggregate-clusterrole unchanged
clusterrolebinding.rbac.authorization.k8s.io/klusterlet unchanged
error validating "STDIN": error validating data: ValidationError(Klusterlet.spec): unknown field "deployOption" in io.open-cluster-management.operator.v1.Klusterlet.spec; if you choose to ignore these errors, turn validation off with --validate=false
Error from server (Forbidden): error when creating "STDIN": serviceaccounts "klusterlet" is forbidden: unable to create new content in namespace open-cluster-management-agent because it is being terminated
Error from server (Forbidden): error when creating "STDIN": deployments.apps "klusterlet" is forbidden: unable to create new content in namespace open-cluster-management-agent because it is being terminated
Error from server (NotFound): error when creating "STDIN": namespaces "open-cluster-management-agent" not found
The cluster cannot be imported because its Klusterlet CRD already exists.
Either the cluster was already imported, or it was not detached completely during a previous detach process.
Detach the existing cluster before trying the import again.%                                                                                                                                                                                                                                        rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
SFdsRlNiVVo2V2xSVk0xUlVRa1pYUldoTldtdEdNRkpIZUc1U2JWcFNUVWhPY21GNmEzaE1NMnhRV2tkek1VMVRPVkJXVkZsMlZGUmtka051Vm5CV1ZteHBVMFJDUlZsclozWlNibWhFVld4V2VsbFZjRlJMTUVwc1UzazVWRlJxU2pOVVIxcHJaRVJzTW1KR2FHdGlNSGN3VjFWR2JtVkVSbTVPUjNoaFVXbHpNVkpXWkdGVU0xWlVXVlJhTkZKWVFVdGpNMFUxWW14bmRsZHNUa2xQUkVaRVdXdFdXbEo2YkVWUFNHUnpZbTVzVVZKRlpIVk9helZXVTBWd1UxTnJaSFpoUjBwRFpFWlpjbUY2YUVkYWVqQTVRMmt3ZEV4VE1IUlNWVFZGU1VWT1JsVnNVa3BTYTJ4RVVWWlNSa3hUTUhSTVV6QkxURk13ZEV4VE1VTlNWV1JLVkdsQ1JGSldTbFZUVlZwS1VUQkdWVkpUTUhSTVV6QjBRMnN4U2xOVldrZGhhMDVFVVZoWk1sb3dSak5UVlVwQ1dqQnNVMUZWY0VaamEwNUdZMnhDUlZGdGJIVldVemxwVmpCNGNGWXlOVmxOVnprelVrWkdXbE5yZEhaWGEyeHZaRzFPVDFGV1JrWlVSVXBTVVZoalMxWkljRVpVUlRGQ1lUQmtRazFXVmtaUmJXaE9VVEZhVjFSWWFFeFdSVVoxVVcxa1QxWnJTa0ppTVZKS1VsZDRNVnBGWkZkbFYwcDBWbXBDU2xKck5YTlhWRTVYWlZkR1dWVnFWa3BTYTNCeldYcEtWMkZCY0dwaVZUVjJVMVZXYTJWWFNYcFdibVJPVld4V00xSllaRnBTUmxwU1ZWVlNSbVF6YUV0V1ZFWkxVMFZzUjFOdVdtbE5NVVp1VmpCU1JtUXdhRzlaTURWT1lXdEdNMVF4VWtKTlJURkZVVmhrVGxKRlJqTkRiR1J2V1RBMVRtRnNWak5VTVZKR1RWVXhWVmRZWkU1U1JVWXpWakp3UW1WVk1WSmpNMlJFVlZac1JWWnNSbEpTTUZZelUyeGFWbVZyVmxoVVZVcFNVakJGZUZaVlZrUmhSVEZQVmtWa1YwMUZiM3BVVjJOTFZXeGpNV0Z0VG5WaVNHUnJVa1ZXVFZSVlJuSlNNRVY0VmxWV1FtVkZNVVJXVjNCT1pESmtibEpYYkU1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRldSbFpSVlVVd1UxVktSV1F3UmpOYU1tUkdVM2R3UW1Jd2JFTlJWa1pFVGpCR2IxWlhPVFpWUjBadVlrVTFUbFZGVmpGbFZUVlhWMnQ0UlVzd2JFMWxSekZvVjJwYVVtSXliSFZYUms1b1kxaFNWR1JVVmpSV1dHdzBZMnBSTVdOcGRGbFhSV3gyVDFkT1VVTnNTVEZWVmxaWFZrWmFXV0ZyYnpKaU1qbHhZVEZ2TlZkVmF6UlZXRVp6VkRKS01sWlVaRE5sVkdScFlXMU9SR1F4YUZGVWJIQlFWREphTUdWcVNuVmtNV1J1WXpKS01tTXdUbFpUYTA1WVUwTjBjVnBJWjB0ak0yaFJZbXRvVEdWdGFIUkxlVGxwVGxWU01GSnNWbkpXTVdSNFdUQmFWV1Z0Y0ZWVFZsWXhUbXBHZVdSVVNsRk5NakZEWkhwU2VGWnNWbmhPTVhBd1VraENiR0pHUmtWVmJrcE1UMVU0TkZkdVZqQmlVWEJQVTBodk1sbFVVakZWUmxvMVlsWnZjbEpGUmxsWFIwcDNaVmRKZG1SVlNqUlpWRTVVWVVkNGJrOVZXVFJhYlRWRVdXNWFORk41T1d4U2VrNU9VMGRHYWxacVRsWlZibFpSVkZoS1ZGZEZTbkJVU0dodVEyeHZlbFp0TVhwTU1GWmFUMVJhUzFsNlZuTlZRemxRWWpKcmVWVnFXbGxNTUZZMFlXNUdkRkZYZDNwVlJGVjRWa04wYWs5RlNURmFiR1IwV1RCS2FsWllTWGxVTW5OMlRsY3hObUY2VlhwWk1WVXlXVEJqUzB3eWRIQlNhMmhvVW01Q2VXRldXWGhrV0doUlZGWldibFZFUlROV2EyUnZZVlJzZWxaclJtNVVWVXBDVVZWa2NWb3laRVpUVlRGS1UxVktRMUpGUmxCUmJXUlBWbXRvVWs5RlNrSmFhbWhHVVd0R1RsRjNjRUpYVm13elUwWkdXbEpHV2xOTlIzaERVV3hzTTFKclJscFRWWFF6VjFWS1ExVldWa2xSV0dSS1VqQk9SR013WkVKVlZsWkhVVzVrVGxGck1VTlRWV1JDVFZaV2ExSllaRVpSYVRrelZWVnNUbEZXYkVORGEwWnRUMFZPUWxWVlJqTlRSa1phVWtaYVUwMUZPVU5SYkd4R1VtdEtVbVJZVGpSYVZFNVlVbTFLVFdOdGVFSlRiRVpRVjFkYWVVNVVTazFTYXpGTlVqQXhRMDlGWkVKTlZsWnJVMWhrVWxkVk1VTlpWVVZMVW10b2RFMUdaR3hYYW1Rd1pGWm9jbEZXYUZCUlZVNUtZV3RzU0dKSGIzbE9iSEF3WkZVeFJWTlZaRVJSTTA1SVVWWkdWbEpyU2pOU1ZVcERVVEZzTTFOclVrSmhWVXB1V2pOS1Exb3dWa2RSYkVacVpIZHdRbUl4YkZoWlZXaFRUVWRPUldJeldrMU5NbVEwVkVjeGNtUlhTa2hXYmxaYVRUQnNNVmxxVGt0aWEzZzJVVmMxUTFvd05WZFRSa2swVWxWc1JWRlhWazVSYm14dVVqTkdRbGRYYUc5WGJUbHJVMFpLTTBOck9YQlBTRnBzVWtWV01WZFlhekZqTVhCWVRsZHdhbUZVVmpKWk1qRnFaR3N4UkZOVlpFSk5WbFpyVTFWR1VsbHJNVU5oTTJSRVVWWnNTRmRxVWtaVVZVWlNVMVZLVGxGVVFraFJNMng2VWpCR1VsVlZTVXRhTTFFMFZrVkdVbEpWU2s1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRXpaRlpSVlVVd1UxVk9RbFZWVGtkbFYzTXhVMFpDZUZWRVRtOVdWazVIWkdzMVYySnRWazFUTVd4YVRtcEZlRlpHU1RKV2QzQlJWa1UxYzFreWVGSmtSMlJvVWtoR00wdDZUVEJUVlhjMVdtNXdUVnBJWkVKVVIxSXhWSGs1WVZwWGVFOU9NblJLVTJsMGRFNTZVakZsVlVWeVdsZHNNRlZzYXpSaE1rMHlUVVJrVldFd1RURk5NMlJ6UTIxc2NscHRNV0ZXZWxGMlZXNWFWVmRxYUU1T2JGWk1TM3BXVm1WdGFFeFBSM0JFV2tWNE1WUlZaRnBVUkZwTVpHNXdXVkl4U2xSYU1tdDZaVlY0Ym1GdFZqTlZXRkpFVlVkMFNsWnViekpTUkVwU1ZWaHZTMUV5ZEdwaFIxWkNZbFZPUzA5Rk1YaGxWWEF4VGxod2MyVnViR0ZVVjNCQ1pHMDFkVkZXVVRCT1dGSlRVVmhvYkdFelNucGtWR3N3WXpGRk1GcFhaR3RWYTA1MVdXeGtWRkpJVWxwT01uUnZTekJLU21KUmNITlRhelZaWWpCSmVHSkZTazVTVlhSS1kxUlNVbEpHVmxCWFJ6bFRXakphYldSVlVtNWhSM0JzVFZaa2VWSjZiRTVVUTNSSldXMXNlbU5UT1RWU2F6bElaREZvUlU5V1NuQlhSR2hIVG01T00wNXNZekJEYlVZeVVWaFdNbEpJVGpaa1YxVXhWRVJPZW1WcVp6RlRlWFJHVVhwU1drd3paRWRXYTFKUFpHeHdkazVHVWxwWFIwWjJUbXh2ZDFwcGRITlZWWFJxVFVoUk5GSkdSbHBsYlhONFZERm9WMlJVYUhsalJFbExaVlZ3VGxGNldtaGlSWGhwVVcxYVVGSkZSazFYYmxwYVUwUmtkVTR5VW5aTlZVWmhZa2hOTUZOVWJHdE5Wa0V3WVcwMWNsSklTbEppTTJoRFRURldlRlZVYkc5V2JYZDZWRVZXVEZWVVkzcGxSVmw0Vkhkd05WTjZWa2hoUlZKRlYwUm9kbFp0V2toVE1Ga3haRk4wYTFwWFRrcGpNR2N3VjFkR1ZXUjZaSFJWUkU1SVVtNW9TMVV6UmpKTmVYTjNZa1pXUjFOdE9YQk9WWGhxVGxkU2FFMVVVVFZqUkd0M1UxZFNla050YUVSU1dHaDVZakIzZUV0NlpIUmpibXhLWVRGb1VWcFZXazVPVmxKdVZIcHNlVTFJU2pKWGJVWkRVbXM1TWxacVNqWk5SMlIzVFhwV1lVMURkRTFPUm1SUllrZEtNVkpYY0U5TU1uZzBWVVZhY0dKcGMwdFRSM2hXWVc1Sk5Gb3hTbnBUVkU1NFdtdHdVRlZWV2pWTWVteDVVekJzUzFWcVFscE1lbWhRWWxoa01FeDZhSFpXUm1SdVpWUkdkRnBIVmtsaVZ6RnhZWHBrY1UxWE5WcGpNMXBFVDFWd1ZGVlVXbUZrWjNCT1lrZFNjMVpHVWt4UmFrNDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTA1ZDJoNE5TNDVkMmg0TlM1ellXNWtZbTk0TVRRd015NXZjR1Z1ZEd4akxtTnZiVG8yTkRRekNpQWdibUZ0WlRvZ1pHVm1ZWFZzZEMxamJIVnpkR1Z5Q21OdmJuUmxlSFJ6T2dvdElHTnZiblJsZUhRNkNpQWdJQ0JqYkhWemRHVnlPaUJrWldaaGRXeDBMV05zZFhOMFpYSUtJQ0FnSUc1aGJXVnpjR0ZqWlRvZ1pHVm1ZWFZzZEFvZ0lDQWdkWE5sY2pvZ1pHVm1ZWFZzZEMxaGRYUm9DaUFnYm1GdFpUb2daR1ZtWVhWc2RDMWpiMjUwWlhoMENtTjFjbkpsYm5RdFkyOXVkR1Y0ZERvZ1pHVm1ZWFZzZEMxamIyNTBaWGgwQ210cGJtUTZJRU52Ym1acFp3cHdjbVZtWlhKbGJtTmxjem9nZTMwS2RYTmxjbk02Q2kwZ2JtRnRaVG9nWkdWbVlYVnNkQzFoZFhSb0NpQWdkWE5sY2pvS0lDQWdJSFJ2YTJWdU9pQmxlVXBvWWtkamFVOXBTbE5WZWtreFRtbEpjMGx0ZEhCYVEwazJTVzVrVUdJd1dtaFZWVTV1VDFWWk0wNVdWbXhTV0VwWVkydEdWbU5zUmpKWWVtUkVWa2hzVm1SWFJtcFdWVkpZVXpKR2RWb3dNVEJTVjAxcFpsRXVaWGxLY0dNelRXbFBhVXB5WkZkS2JHTnROV3hrUjFaNlRETk9iR051V25CWk1sWm9XVEpPZG1SWE5UQkphWGRwWVROV2FWcFlTblZhV0ZKc1kzazFjR0o1T1hwYVdFb3lZVmRPYkZsWFRtcGlNMVoxWkVNNWRWbFhNV3hqTTBKb1dUSlZhVTlwU21obGJsWjVXbGRPYzJSWVRqQmFXRWxwVEVOS2NtUlhTbXhqYlRWc1pFZFdla3h0YkhaTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1Fd3pUbXhaTTBwc1pFTTFkVmxYTVd4SmFtOXBXVmh3TVdOdFZtcGlTRlo2WkVkV2VVeFhTblppTTFKNlpFaEthR05ETVhwWlV6RXdZakowYkdKcE1YaGpibEowWkdsSmMwbHRkREZaYlZaNVltMVdNRnBZVFhWaFZ6aDJZekpXZVdSdGJHcGFWMFpxV1RJNU1XSnVVWFpqTWxaNVpHMXNhbHBUTVdoWk1rNTJaRmMxTUV4dE5XaGlWMVZwVDJsS2FHVnVWbmxhVjA1elpGaE9NRnBZU1hSWmJUbDJaRWhPTUdOdFJuZE1XRTVvU1dsM2FXRXpWbWxhV0VwMVdsaFNiR041TlhCaWVUbDZXbGhLTW1GWFRteFpWMDVxWWpOV2RXUkRPWHBhV0VveVlWZE9iRXhYUm1wWk1qa3hZbTVSZFdSWGJHdEphbTlwV1ZkUmVrOUhWVEphUkdOMFdUSlZOVTFETURCUFJFVXhURlJuTWsxWFRYUk9iVkpzV20xVk1rMXFZekZOUjFFd1NXbDNhV016Vm1sSmFtOXBZek5zZW1SSFZuUlBiazVzWTI1YWNGa3lWbWhaTWs1MlpGYzFNRTl0Umpaa1dFcHNXVEo0TVdNelVteGphbkJvWlc1V2VWcFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaEpiakF1Y0U1V05qY3lWbk50WkhKNVREUjViVkpUYlROR2FIRTBhbmhaTjNWVWJFRkdhWE5SWmpGalpYUXdiVTl4VG14SE9XbFRjRTlmVW5kbldXVjRkbEpWVmtodlEyZzRNSGcxZFVKaWVYTmhOMDVmZVZaQk9XTkVVa3hFVWpoSVZISkxkMXBtU0VkbFdGOUpiMk5UUm5wWE9VWnFVRmRDZWtabFdHODNOSEZrYmpRMFQwUnRZWEp5YzNsWU5EbEVaamRPZFhnNGQyUmlUelZ3TFdod2NFc3hNVTl1U3pWS2RrMXNWV0Z6T0ZCMWRVbDBUV2xOYTBOaFVtNTJWakZTVjB0b1dWUm9NRWR1Y25CYWRVbFNWRXhhVmw5c1ozcGtZM0JMVFMxamNuVTVZVEEzUzFkdk0wbHphRVF5V0V0VWF6QXlOSGcxVEZsd2FWcEVhRk5ZWlZkblYzSjJNSFV4ZURWc2EySTBhalZyU1VVNE5ERTVNMVJaT0ZKNWRVZzJSMnBPTFd0UlVVYzRlVTlLTWkxM1RWcGpUVkpVVDE5UWVuTk5TSEl6WjFNemEwTk1SRmMzTFV4SFMwaHRTR2RVVjFGeGRXbzFPSEE0VkY5QlJUaFFUelpJTW5NMmNVOUZaR2xQVnpoSVJHTlFMUzB0YjFaa09FMTZhMVZ1VjA1RGExRk5UeTFuUWtsS1p6QmFNVmh1VkhkZmVHZFJabGRRUzNSVVkyMU1RM2RMVEcxcllWTTFOVkJ5V1VwUlpsWm9kMjh5UlhST1dYVkJjWFl5ZVhaUGExZElja2hRVkhsV01UaENTVnAwV2t4elQyMTVVRjgzTW5BM2FqZDVkM05CZGpSb1pHdHVXVmt4ZUVOeVoybHFNWFp4YVVnNFkyYzFkVFpaY0VsaWJUWjRaa0ZDV0dwekxVNXphbDltU1RseFZ6aFlXRGRLVFdWMlUyOTZRbGd3TkZsVVkwRnZkemRWZVdkbWMycDRaemg2WW1sV01FZzFha2QzWjBGdGEyWjRWR3BDWDFkcVVWQllTVll4ZVcxbll5MU9UVXRmV1hoWlpVUlJjWFpCVFY5eE5YUmlkRWRNZHpkc1JreFliamgwT0RsdWNXTlZTa1JYTFdnNWQwa3RjVEZ1VG5kWGFuWXhhamhIT1V4elpsSTNWemg2WkZGeGFUZ3dSQzA1Umt0TmQyc3RjamxYUVhGR2VHaHNSbEVLIgoKLS0tCmFwaVZlcnNpb246IG9wZXJhdG9yLm9wZW4tY2x1c3Rlci1tYW5hZ2VtZW50LmlvL3YxCmtpbmQ6IEtsdXN0ZXJsZXQKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApzcGVjOgogIGRlcGxveU9wdGlvbjoKICAgIG1vZGU6IERlZmF1bHQKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvcmVnaXN0cmF0aW9uLXJoZWw4QHNoYTI1NjpiY2M2ZDEyYmE0ZjFkY2Q3ZmEwMDg2M2YyODhlZDhiYzkxM2M2NjViYWNlYmFjNzliMzYwODgwZDFjZTMzMDUwIgogIHdvcmtJbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvd29yay1yaGVsOEBzaGEyNTY6YTJmYmI0ZmFiMDA3MzU2M2I4ZWQyODk1ODU5Y2Q4YjcwNTgzNTM0MTk0YTYyMjI4NzExZTBjMzc4YTk1NjU5MiIKICBjbHVzdGVyTmFtZTogImF6dXJlY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
Error from server (AlreadyExists): error when creating "STDIN": customresourcedefinitions.apiextensions.k8s.io "klusterlets.operator.open-cluster-management.io" already exists
The cluster cannot be imported because its Klusterlet CRD already exists.
Either the cluster was already imported, or it was not detached completely during a previous detach process.
Detach the existing cluster before trying the import again.%                                                                                                                                                                                                                                        rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
SFdsRlNiVVo2V2xSVk0xUlVRa1pYUldoTldtdEdNRkpIZUc1U2JWcFNUVWhPY21GNmEzaE1NMnhRV2tkek1VMVRPVkJXVkZsMlZGUmtka051Vm5CV1ZteHBVMFJDUlZsclozWlNibWhFVld4V2VsbFZjRlJMTUVwc1UzazVWRlJxU2pOVVIxcHJaRVJzTW1KR2FHdGlNSGN3VjFWR2JtVkVSbTVPUjNoaFVXbHpNVkpXWkdGVU0xWlVXVlJhTkZKWVFVdGpNMFUxWW14bmRsZHNUa2xQUkVaRVdXdFdXbEo2YkVWUFNHUnpZbTVzVVZKRlpIVk9helZXVTBWd1UxTnJaSFpoUjBwRFpFWlpjbUY2YUVkYWVqQTVRMmt3ZEV4VE1IUlNWVFZGU1VWT1JsVnNVa3BTYTJ4RVVWWlNSa3hUTUhSTVV6QkxURk13ZEV4VE1VTlNWV1JLVkdsQ1JGSldTbFZUVlZwS1VUQkdWVkpUTUhSTVV6QjBRMnN4U2xOVldrZGhhMDVFVVZoWk1sb3dSak5UVlVwQ1dqQnNVMUZWY0VaamEwNUdZMnhDUlZGdGJIVldVemxwVmpCNGNGWXlOVmxOVnprelVrWkdXbE5yZEhaWGEyeHZaRzFPVDFGV1JrWlVSVXBTVVZoalMxWkljRVpVUlRGQ1lUQmtRazFXVmtaUmJXaE9VVEZhVjFSWWFFeFdSVVoxVVcxa1QxWnJTa0ppTVZKS1VsZDRNVnBGWkZkbFYwcDBWbXBDU2xKck5YTlhWRTVYWlZkR1dWVnFWa3BTYTNCeldYcEtWMkZCY0dwaVZUVjJVMVZXYTJWWFNYcFdibVJPVld4V00xSllaRnBTUmxwU1ZWVlNSbVF6YUV0V1ZFWkxVMFZzUjFOdVdtbE5NVVp1VmpCU1JtUXdhRzlaTURWT1lXdEdNMVF4VWtKTlJURkZVVmhrVGxKRlJqTkRiR1J2V1RBMVRtRnNWak5VTVZKR1RWVXhWVmRZWkU1U1JVWXpWakp3UW1WVk1WSmpNMlJFVlZac1JWWnNSbEpTTUZZelUyeGFWbVZyVmxoVVZVcFNVakJGZUZaVlZrUmhSVEZQVmtWa1YwMUZiM3BVVjJOTFZXeGpNV0Z0VG5WaVNHUnJVa1ZXVFZSVlJuSlNNRVY0VmxWV1FtVkZNVVJXVjNCT1pESmtibEpYYkU1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRldSbFpSVlVVd1UxVktSV1F3UmpOYU1tUkdVM2R3UW1Jd2JFTlJWa1pFVGpCR2IxWlhPVFpWUjBadVlrVTFUbFZGVmpGbFZUVlhWMnQ0UlVzd2JFMWxSekZvVjJwYVVtSXliSFZYUms1b1kxaFNWR1JVVmpSV1dHdzBZMnBSTVdOcGRGbFhSV3gyVDFkT1VVTnNTVEZWVmxaWFZrWmFXV0ZyYnpKaU1qbHhZVEZ2TlZkVmF6UlZXRVp6VkRKS01sWlVaRE5sVkdScFlXMU9SR1F4YUZGVWJIQlFWREphTUdWcVNuVmtNV1J1WXpKS01tTXdUbFpUYTA1WVUwTjBjVnBJWjB0ak0yaFJZbXRvVEdWdGFIUkxlVGxwVGxWU01GSnNWbkpXTVdSNFdUQmFWV1Z0Y0ZWVFZsWXhUbXBHZVdSVVNsRk5NakZEWkhwU2VGWnNWbmhPTVhBd1VraENiR0pHUmtWVmJrcE1UMVU0TkZkdVZqQmlVWEJQVTBodk1sbFVVakZWUmxvMVlsWnZjbEpGUmxsWFIwcDNaVmRKZG1SVlNqUlpWRTVVWVVkNGJrOVZXVFJhYlRWRVdXNWFORk41T1d4U2VrNU9VMGRHYWxacVRsWlZibFpSVkZoS1ZGZEZTbkJVU0dodVEyeHZlbFp0TVhwTU1GWmFUMVJhUzFsNlZuTlZRemxRWWpKcmVWVnFXbGxNTUZZMFlXNUdkRkZYZDNwVlJGVjRWa04wYWs5RlNURmFiR1IwV1RCS2FsWllTWGxVTW5OMlRsY3hObUY2VlhwWk1WVXlXVEJqUzB3eWRIQlNhMmhvVW01Q2VXRldXWGhrV0doUlZGWldibFZFUlROV2EyUnZZVlJzZWxaclJtNVVWVXBDVVZWa2NWb3laRVpUVlRGS1UxVktRMUpGUmxCUmJXUlBWbXRvVWs5RlNrSmFhbWhHVVd0R1RsRjNjRUpYVm13elUwWkdXbEpHV2xOTlIzaERVV3hzTTFKclJscFRWWFF6VjFWS1ExVldWa2xSV0dSS1VqQk9SR013WkVKVlZsWkhVVzVrVGxGck1VTlRWV1JDVFZaV2ExSllaRVpSYVRrelZWVnNUbEZXYkVORGEwWnRUMFZPUWxWVlJqTlRSa1phVWtaYVUwMUZPVU5SYkd4R1VtdEtVbVJZVGpSYVZFNVlVbTFLVFdOdGVFSlRiRVpRVjFkYWVVNVVTazFTYXpGTlVqQXhRMDlGWkVKTlZsWnJVMWhrVWxkVk1VTlpWVVZMVW10b2RFMUdaR3hYYW1Rd1pGWm9jbEZXYUZCUlZVNUtZV3RzU0dKSGIzbE9iSEF3WkZVeFJWTlZaRVJSTTA1SVVWWkdWbEpyU2pOU1ZVcERVVEZzTTFOclVrSmhWVXB1V2pOS1Exb3dWa2RSYkVacVpIZHdRbUl4YkZoWlZXaFRUVWRPUldJeldrMU5NbVEwVkVjeGNtUlhTa2hXYmxaYVRUQnNNVmxxVGt0aWEzZzJVVmMxUTFvd05WZFRSa2swVWxWc1JWRlhWazVSYm14dVVqTkdRbGRYYUc5WGJUbHJVMFpLTTBOck9YQlBTRnBzVWtWV01WZFlhekZqTVhCWVRsZHdhbUZVVmpKWk1qRnFaR3N4UkZOVlpFSk5WbFpyVTFWR1VsbHJNVU5oTTJSRVVWWnNTRmRxVWtaVVZVWlNVMVZLVGxGVVFraFJNMng2VWpCR1VsVlZTVXRhTTFFMFZrVkdVbEpWU2s1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRXpaRlpSVlVVd1UxVk9RbFZWVGtkbFYzTXhVMFpDZUZWRVRtOVdWazVIWkdzMVYySnRWazFUTVd4YVRtcEZlRlpHU1RKV2QzQlJWa1UxYzFreWVGSmtSMlJvVWtoR00wdDZUVEJUVlhjMVdtNXdUVnBJWkVKVVIxSXhWSGs1WVZwWGVFOU9NblJLVTJsMGRFNTZVakZsVlVWeVdsZHNNRlZzYXpSaE1rMHlUVVJrVldFd1RURk5NMlJ6UTIxc2NscHRNV0ZXZWxGMlZXNWFWVmRxYUU1T2JGWk1TM3BXVm1WdGFFeFBSM0JFV2tWNE1WUlZaRnBVUkZwTVpHNXdXVkl4U2xSYU1tdDZaVlY0Ym1GdFZqTlZXRkpFVlVkMFNsWnViekpTUkVwU1ZWaHZTMUV5ZEdwaFIxWkNZbFZPUzA5Rk1YaGxWWEF4VGxod2MyVnViR0ZVVjNCQ1pHMDFkVkZXVVRCT1dGSlRVVmhvYkdFelNucGtWR3N3WXpGRk1GcFhaR3RWYTA1MVdXeGtWRkpJVWxwT01uUnZTekJLU21KUmNITlRhelZaWWpCSmVHSkZTazVTVlhSS1kxUlNVbEpHVmxCWFJ6bFRXakphYldSVlVtNWhSM0JzVFZaa2VWSjZiRTVVUTNSSldXMXNlbU5UT1RWU2F6bElaREZvUlU5V1NuQlhSR2hIVG01T00wNXNZekJEYlVZeVVWaFdNbEpJVGpaa1YxVXhWRVJPZW1WcVp6RlRlWFJHVVhwU1drd3paRWRXYTFKUFpHeHdkazVHVWxwWFIwWjJUbXh2ZDFwcGRITlZWWFJxVFVoUk5GSkdSbHBsYlhONFZERm9WMlJVYUhsalJFbExaVlZ3VGxGNldtaGlSWGhwVVcxYVVGSkZSazFYYmxwYVUwUmtkVTR5VW5aTlZVWmhZa2hOTUZOVWJHdE5Wa0V3WVcwMWNsSklTbEppTTJoRFRURldlRlZVYkc5V2JYZDZWRVZXVEZWVVkzcGxSVmw0Vkhkd05WTjZWa2hoUlZKRlYwUm9kbFp0V2toVE1Ga3haRk4wYTFwWFRrcGpNR2N3VjFkR1ZXUjZaSFJWUkU1SVVtNW9TMVV6UmpKTmVYTjNZa1pXUjFOdE9YQk9WWGhxVGxkU2FFMVVVVFZqUkd0M1UxZFNla050YUVSU1dHaDVZakIzZUV0NlpIUmpibXhLWVRGb1VWcFZXazVPVmxKdVZIcHNlVTFJU2pKWGJVWkRVbXM1TWxacVNqWk5SMlIzVFhwV1lVMURkRTFPUm1SUllrZEtNVkpYY0U5TU1uZzBWVVZhY0dKcGMwdFRSM2hXWVc1Sk5Gb3hTbnBUVkU1NFdtdHdVRlZWV2pWTWVteDVVekJzUzFWcVFscE1lbWhRWWxoa01FeDZhSFpXUm1SdVpWUkdkRnBIVmtsaVZ6RnhZWHBrY1UxWE5WcGpNMXBFVDFWd1ZGVlVXbUZrWjNCT1lrZFNjMVpHVWt4UmFrNDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTA1ZDJoNE5TNDVkMmg0TlM1ellXNWtZbTk0TVRRd015NXZjR1Z1ZEd4akxtTnZiVG8yTkRRekNpQWdibUZ0WlRvZ1pHVm1ZWFZzZEMxamJIVnpkR1Z5Q21OdmJuUmxlSFJ6T2dvdElHTnZiblJsZUhRNkNpQWdJQ0JqYkhWemRHVnlPaUJrWldaaGRXeDBMV05zZFhOMFpYSUtJQ0FnSUc1aGJXVnpjR0ZqWlRvZ1pHVm1ZWFZzZEFvZ0lDQWdkWE5sY2pvZ1pHVm1ZWFZzZEMxaGRYUm9DaUFnYm1GdFpUb2daR1ZtWVhWc2RDMWpiMjUwWlhoMENtTjFjbkpsYm5RdFkyOXVkR1Y0ZERvZ1pHVm1ZWFZzZEMxamIyNTBaWGgwQ210cGJtUTZJRU52Ym1acFp3cHdjbVZtWlhKbGJtTmxjem9nZTMwS2RYTmxjbk02Q2kwZ2JtRnRaVG9nWkdWbVlYVnNkQzFoZFhSb0NpQWdkWE5sY2pvS0lDQWdJSFJ2YTJWdU9pQmxlVXBvWWtkamFVOXBTbE5WZWtreFRtbEpjMGx0ZEhCYVEwazJTVzVrVUdJd1dtaFZWVTV1VDFWWk0wNVdWbXhTV0VwWVkydEdWbU5zUmpKWWVtUkVWa2hzVm1SWFJtcFdWVkpZVXpKR2RWb3dNVEJTVjAxcFpsRXVaWGxLY0dNelRXbFBhVXB5WkZkS2JHTnROV3hrUjFaNlRETk9iR051V25CWk1sWm9XVEpPZG1SWE5UQkphWGRwWVROV2FWcFlTblZhV0ZKc1kzazFjR0o1T1hwYVdFb3lZVmRPYkZsWFRtcGlNMVoxWkVNNWRWbFhNV3hqTTBKb1dUSlZhVTlwU21obGJsWjVXbGRPYzJSWVRqQmFXRWxwVEVOS2NtUlhTbXhqYlRWc1pFZFdla3h0YkhaTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1Fd3pUbXhaTTBwc1pFTTFkVmxYTVd4SmFtOXBXVmh3TVdOdFZtcGlTRlo2WkVkV2VVeFhTblppTTFKNlpFaEthR05ETVhwWlV6RXdZakowYkdKcE1YaGpibEowWkdsSmMwbHRkREZaYlZaNVltMVdNRnBZVFhWaFZ6aDJZekpXZVdSdGJHcGFWMFpxV1RJNU1XSnVVWFpqTWxaNVpHMXNhbHBUTVdoWk1rNTJaRmMxTUV4dE5XaGlWMVZwVDJsS2FHVnVWbmxhVjA1elpGaE9NRnBZU1hSWmJUbDJaRWhPTUdOdFJuZE1XRTVvU1dsM2FXRXpWbWxhV0VwMVdsaFNiR041TlhCaWVUbDZXbGhLTW1GWFRteFpWMDVxWWpOV2RXUkRPWHBhV0VveVlWZE9iRXhYUm1wWk1qa3hZbTVSZFdSWGJHdEphbTlwV1ZkUmVrOUhWVEphUkdOMFdUSlZOVTFETURCUFJFVXhURlJuTWsxWFRYUk9iVkpzV20xVk1rMXFZekZOUjFFd1NXbDNhV016Vm1sSmFtOXBZek5zZW1SSFZuUlBiazVzWTI1YWNGa3lWbWhaTWs1MlpGYzFNRTl0Umpaa1dFcHNXVEo0TVdNelVteGphbkJvWlc1V2VWcFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaEpiakF1Y0U1V05qY3lWbk50WkhKNVREUjViVkpUYlROR2FIRTBhbmhaTjNWVWJFRkdhWE5SWmpGalpYUXdiVTl4VG14SE9XbFRjRTlmVW5kbldXVjRkbEpWVmtodlEyZzRNSGcxZFVKaWVYTmhOMDVmZVZaQk9XTkVVa3hFVWpoSVZISkxkMXBtU0VkbFdGOUpiMk5UUm5wWE9VWnFVRmRDZWtabFdHODNOSEZrYmpRMFQwUnRZWEp5YzNsWU5EbEVaamRPZFhnNGQyUmlUelZ3TFdod2NFc3hNVTl1U3pWS2RrMXNWV0Z6T0ZCMWRVbDBUV2xOYTBOaFVtNTJWakZTVjB0b1dWUm9NRWR1Y25CYWRVbFNWRXhhVmw5c1ozcGtZM0JMVFMxamNuVTVZVEEzUzFkdk0wbHphRVF5V0V0VWF6QXlOSGcxVEZsd2FWcEVhRk5ZWlZkblYzSjJNSFV4ZURWc2EySTBhalZyU1VVNE5ERTVNMVJaT0ZKNWRVZzJSMnBPTFd0UlVVYzRlVTlLTWkxM1RWcGpUVkpVVDE5UWVuTk5TSEl6WjFNemEwTk1SRmMzTFV4SFMwaHRTR2RVVjFGeGRXbzFPSEE0VkY5QlJUaFFUelpJTW5NMmNVOUZaR2xQVnpoSVJHTlFMUzB0YjFaa09FMTZhMVZ1VjA1RGExRk5UeTFuUWtsS1p6QmFNVmh1VkhkZmVHZFJabGRRUzNSVVkyMU1RM2RMVEcxcllWTTFOVkJ5V1VwUlpsWm9kMjh5UlhST1dYVkJjWFl5ZVhaUGExZElja2hRVkhsV01UaENTVnAwV2t4elQyMTVVRjgzTW5BM2FqZDVkM05CZGpSb1pHdHVXVmt4ZUVOeVoybHFNWFp4YVVnNFkyYzFkVFpaY0VsaWJUWjRaa0ZDV0dwekxVNXphbDltU1RseFZ6aFlXRGRLVFdWMlUyOTZRbGd3TkZsVVkwRnZkemRWZVdkbWMycDRaemg2WW1sV01FZzFha2QzWjBGdGEyWjRWR3BDWDFkcVVWQllTVll4ZVcxbll5MU9UVXRmV1hoWlpVUlJjWFpCVFY5eE5YUmlkRWRNZHpkc1JreFliamgwT0RsdWNXTlZTa1JYTFdnNWQwa3RjVEZ1VG5kWGFuWXhhamhIT1V4elpsSTNWemg2WkZGeGFUZ3dSQzA1Umt0TmQyc3RjamxYUVhGR2VHaHNSbEVLIgoKLS0tCmFwaVZlcnNpb246IG9wZXJhdG9yLm9wZW4tY2x1c3Rlci1tYW5hZ2VtZW50LmlvL3YxCmtpbmQ6IEtsdXN0ZXJsZXQKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApzcGVjOgogIGRlcGxveU9wdGlvbjoKICAgIG1vZGU6IERlZmF1bHQKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvcmVnaXN0cmF0aW9uLXJoZWw4QHNoYTI1NjpiY2M2ZDEyYmE0ZjFkY2Q3ZmEwMDg2M2YyODhlZDhiYzkxM2M2NjViYWNlYmFjNzliMzYwODgwZDFjZTMzMDUwIgogIHdvcmtJbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvd29yay1yaGVsOEBzaGEyNTY6YTJmYmI0ZmFiMDA3MzU2M2I4ZWQyODk1ODU5Y2Q4YjcwNTgzNTM0MTk0YTYyMjI4NzExZTBjMzc4YTk1NjU5MiIKICBjbHVzdGVyTmFtZTogImF6dXJlY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
Error from server (AlreadyExists): error when creating "STDIN": customresourcedefinitions.apiextensions.k8s.io "klusterlets.operator.open-cluster-management.io" already exists
The cluster cannot be imported because its Klusterlet CRD already exists.
Either the cluster was already imported, or it was not detached completely during a previous detach process.
Detach the existing cluster before trying the import again.%                                                                                                                                                                                                                                        rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
SFdsRlNiVVo2V2xSVk0xUlVRa1pYUldoTldtdEdNRkpIZUc1U2JWcFNUVWhPY21GNmEzaE1NMnhRV2tkek1VMVRPVkJXVkZsMlZGUmtka051Vm5CV1ZteHBVMFJDUlZsclozWlNibWhFVld4V2VsbFZjRlJMTUVwc1UzazVWRlJxU2pOVVIxcHJaRVJzTW1KR2FHdGlNSGN3VjFWR2JtVkVSbTVPUjNoaFVXbHpNVkpXWkdGVU0xWlVXVlJhTkZKWVFVdGpNMFUxWW14bmRsZHNUa2xQUkVaRVdXdFdXbEo2YkVWUFNHUnpZbTVzVVZKRlpIVk9helZXVTBWd1UxTnJaSFpoUjBwRFpFWlpjbUY2YUVkYWVqQTVRMmt3ZEV4VE1IUlNWVFZGU1VWT1JsVnNVa3BTYTJ4RVVWWlNSa3hUTUhSTVV6QkxURk13ZEV4VE1VTlNWV1JLVkdsQ1JGSldTbFZUVlZwS1VUQkdWVkpUTUhSTVV6QjBRMnN4U2xOVldrZGhhMDVFVVZoWk1sb3dSak5UVlVwQ1dqQnNVMUZWY0VaamEwNUdZMnhDUlZGdGJIVldVemxwVmpCNGNGWXlOVmxOVnprelVrWkdXbE5yZEhaWGEyeHZaRzFPVDFGV1JrWlVSVXBTVVZoalMxWkljRVpVUlRGQ1lUQmtRazFXVmtaUmJXaE9VVEZhVjFSWWFFeFdSVVoxVVcxa1QxWnJTa0ppTVZKS1VsZDRNVnBGWkZkbFYwcDBWbXBDU2xKck5YTlhWRTVYWlZkR1dWVnFWa3BTYTNCeldYcEtWMkZCY0dwaVZUVjJVMVZXYTJWWFNYcFdibVJPVld4V00xSllaRnBTUmxwU1ZWVlNSbVF6YUV0V1ZFWkxVMFZzUjFOdVdtbE5NVVp1VmpCU1JtUXdhRzlaTURWT1lXdEdNMVF4VWtKTlJURkZVVmhrVGxKRlJqTkRiR1J2V1RBMVRtRnNWak5VTVZKR1RWVXhWVmRZWkU1U1JVWXpWakp3UW1WVk1WSmpNMlJFVlZac1JWWnNSbEpTTUZZelUyeGFWbVZyVmxoVVZVcFNVakJGZUZaVlZrUmhSVEZQVmtWa1YwMUZiM3BVVjJOTFZXeGpNV0Z0VG5WaVNHUnJVa1ZXVFZSVlJuSlNNRVY0VmxWV1FtVkZNVVJXVjNCT1pESmtibEpYYkU1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRldSbFpSVlVVd1UxVktSV1F3UmpOYU1tUkdVM2R3UW1Jd2JFTlJWa1pFVGpCR2IxWlhPVFpWUjBadVlrVTFUbFZGVmpGbFZUVlhWMnQ0UlVzd2JFMWxSekZvVjJwYVVtSXliSFZYUms1b1kxaFNWR1JVVmpSV1dHdzBZMnBSTVdOcGRGbFhSV3gyVDFkT1VVTnNTVEZWVmxaWFZrWmFXV0ZyYnpKaU1qbHhZVEZ2TlZkVmF6UlZXRVp6VkRKS01sWlVaRE5sVkdScFlXMU9SR1F4YUZGVWJIQlFWREphTUdWcVNuVmtNV1J1WXpKS01tTXdUbFpUYTA1WVUwTjBjVnBJWjB0ak0yaFJZbXRvVEdWdGFIUkxlVGxwVGxWU01GSnNWbkpXTVdSNFdUQmFWV1Z0Y0ZWVFZsWXhUbXBHZVdSVVNsRk5NakZEWkhwU2VGWnNWbmhPTVhBd1VraENiR0pHUmtWVmJrcE1UMVU0TkZkdVZqQmlVWEJQVTBodk1sbFVVakZWUmxvMVlsWnZjbEpGUmxsWFIwcDNaVmRKZG1SVlNqUlpWRTVVWVVkNGJrOVZXVFJhYlRWRVdXNWFORk41T1d4U2VrNU9VMGRHYWxacVRsWlZibFpSVkZoS1ZGZEZTbkJVU0dodVEyeHZlbFp0TVhwTU1GWmFUMVJhUzFsNlZuTlZRemxRWWpKcmVWVnFXbGxNTUZZMFlXNUdkRkZYZDNwVlJGVjRWa04wYWs5RlNURmFiR1IwV1RCS2FsWllTWGxVTW5OMlRsY3hObUY2VlhwWk1WVXlXVEJqUzB3eWRIQlNhMmhvVW01Q2VXRldXWGhrV0doUlZGWldibFZFUlROV2EyUnZZVlJzZWxaclJtNVVWVXBDVVZWa2NWb3laRVpUVlRGS1UxVktRMUpGUmxCUmJXUlBWbXRvVWs5RlNrSmFhbWhHVVd0R1RsRjNjRUpYVm13elUwWkdXbEpHV2xOTlIzaERVV3hzTTFKclJscFRWWFF6VjFWS1ExVldWa2xSV0dSS1VqQk9SR013WkVKVlZsWkhVVzVrVGxGck1VTlRWV1JDVFZaV2ExSllaRVpSYVRrelZWVnNUbEZXYkVORGEwWnRUMFZPUWxWVlJqTlRSa1phVWtaYVUwMUZPVU5SYkd4R1VtdEtVbVJZVGpSYVZFNVlVbTFLVFdOdGVFSlRiRVpRVjFkYWVVNVVTazFTYXpGTlVqQXhRMDlGWkVKTlZsWnJVMWhrVWxkVk1VTlpWVVZMVW10b2RFMUdaR3hYYW1Rd1pGWm9jbEZXYUZCUlZVNUtZV3RzU0dKSGIzbE9iSEF3WkZVeFJWTlZaRVJSTTA1SVVWWkdWbEpyU2pOU1ZVcERVVEZzTTFOclVrSmhWVXB1V2pOS1Exb3dWa2RSYkVacVpIZHdRbUl4YkZoWlZXaFRUVWRPUldJeldrMU5NbVEwVkVjeGNtUlhTa2hXYmxaYVRUQnNNVmxxVGt0aWEzZzJVVmMxUTFvd05WZFRSa2swVWxWc1JWRlhWazVSYm14dVVqTkdRbGRYYUc5WGJUbHJVMFpLTTBOck9YQlBTRnBzVWtWV01WZFlhekZqTVhCWVRsZHdhbUZVVmpKWk1qRnFaR3N4UkZOVlpFSk5WbFpyVTFWR1VsbHJNVU5oTTJSRVVWWnNTRmRxVWtaVVZVWlNVMVZLVGxGVVFraFJNMng2VWpCR1VsVlZTVXRhTTFFMFZrVkdVbEpWU2s1UlZFSklVVEZPZUZJeFRrcFphazVGVlZWV1ExRXpaRlpSVlVVd1UxVk9RbFZWVGtkbFYzTXhVMFpDZUZWRVRtOVdWazVIWkdzMVYySnRWazFUTVd4YVRtcEZlRlpHU1RKV2QzQlJWa1UxYzFreWVGSmtSMlJvVWtoR00wdDZUVEJUVlhjMVdtNXdUVnBJWkVKVVIxSXhWSGs1WVZwWGVFOU9NblJLVTJsMGRFNTZVakZsVlVWeVdsZHNNRlZzYXpSaE1rMHlUVVJrVldFd1RURk5NMlJ6UTIxc2NscHRNV0ZXZWxGMlZXNWFWVmRxYUU1T2JGWk1TM3BXVm1WdGFFeFBSM0JFV2tWNE1WUlZaRnBVUkZwTVpHNXdXVkl4U2xSYU1tdDZaVlY0Ym1GdFZqTlZXRkpFVlVkMFNsWnViekpTUkVwU1ZWaHZTMUV5ZEdwaFIxWkNZbFZPUzA5Rk1YaGxWWEF4VGxod2MyVnViR0ZVVjNCQ1pHMDFkVkZXVVRCT1dGSlRVVmhvYkdFelNucGtWR3N3WXpGRk1GcFhaR3RWYTA1MVdXeGtWRkpJVWxwT01uUnZTekJLU21KUmNITlRhelZaWWpCSmVHSkZTazVTVlhSS1kxUlNVbEpHVmxCWFJ6bFRXakphYldSVlVtNWhSM0JzVFZaa2VWSjZiRTVVUTNSSldXMXNlbU5UT1RWU2F6bElaREZvUlU5V1NuQlhSR2hIVG01T00wNXNZekJEYlVZeVVWaFdNbEpJVGpaa1YxVXhWRVJPZW1WcVp6RlRlWFJHVVhwU1drd3paRWRXYTFKUFpHeHdkazVHVWxwWFIwWjJUbXh2ZDFwcGRITlZWWFJxVFVoUk5GSkdSbHBsYlhONFZERm9WMlJVYUhsalJFbExaVlZ3VGxGNldtaGlSWGhwVVcxYVVGSkZSazFYYmxwYVUwUmtkVTR5VW5aTlZVWmhZa2hOTUZOVWJHdE5Wa0V3WVcwMWNsSklTbEppTTJoRFRURldlRlZVYkc5V2JYZDZWRVZXVEZWVVkzcGxSVmw0Vkhkd05WTjZWa2hoUlZKRlYwUm9kbFp0V2toVE1Ga3haRk4wYTFwWFRrcGpNR2N3VjFkR1ZXUjZaSFJWUkU1SVVtNW9TMVV6UmpKTmVYTjNZa1pXUjFOdE9YQk9WWGhxVGxkU2FFMVVVVFZqUkd0M1UxZFNla050YUVSU1dHaDVZakIzZUV0NlpIUmpibXhLWVRGb1VWcFZXazVPVmxKdVZIcHNlVTFJU2pKWGJVWkRVbXM1TWxacVNqWk5SMlIzVFhwV1lVMURkRTFPUm1SUllrZEtNVkpYY0U5TU1uZzBWVVZhY0dKcGMwdFRSM2hXWVc1Sk5Gb3hTbnBUVkU1NFdtdHdVRlZWV2pWTWVteDVVekJzUzFWcVFscE1lbWhRWWxoa01FeDZhSFpXUm1SdVpWUkdkRnBIVmtsaVZ6RnhZWHBrY1UxWE5WcGpNMXBFVDFWd1ZGVlVXbUZrWjNCT1lrZFNjMVpHVWt4UmFrNDJZVVpTYjFacVJYSlhSbVJhWTBSYWVXRnRVVEZUYkdONFpXMUtWMVl3Vm5KVVJUVTBVbFJrU0ZOc1VtOVNWbFpJVFROT05sb3dTbGRTTVVFelkwWk9XRlpHVmxWak0wWlpRMjAxVFZWdFNqTlRSVGwyWTFSa2IxTklaRzVRVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpzYkVWUk1FNURVbGRzYmxGWVpFcFJhMFp1VTFaR1VsRlZXWHBUVmxKdFZsUmFWbE42VVROaWJVWjRWVVZrVWxNelVqWlJWVFZEV2pKMGVHRkhkSEJTZW13elRVVktRbFZZVGtkUlZWSkNUSGR3VGxVeFJqTlRWMlJhVWtaYVVsVlZkRVpsU0ZKR1dWWmthMk5IVWtoU2JrNUtVbXMxZDFkcVNURmhSMUpKVm01c1lWVXdTbFpaTWpWWFpXMVNSRkZyVW1sbFZGSTBVbTV3UWxaclNtNVViRnBEVVZVeFZVTnJVbkpWYkZKWFVUQktWRmxxU1RWTlJXeEdWR3RLU2xKdFpEWlVWVWt3VjBWU1ZWTllhRTVTUlZZMVZGVlNSazVWTVZWVldHUk9UVmM1V1ZKR1VrcE5SVEZGWVROd1RsSkZWVEJVVmxKU1pEQXdlR0l6WTB0V1NIQkdWRVV4UW1Fd1pFSk5WbFpHVVcxb1RsRXhXbGRVV0doTVZrVkdkVkZ0WkU5V2EwcENZakZTU2xKWGVERmFSV1JYWlZkS2RGWnFRa3BTYXpWelYxUk9WMlZYUmxsVmFsWktVbXR3YzFsNlNsZGhRWEJxWWxVMWRsTlZWbXRsVjBsNlZtNWtUbFZzVmpOU1dHUmFVa1phVWxWVlVrWmtNMmhMVmxSR1MxTkZiRWRUYmxwcFRURkdibFl3VWtaa01tUnVVMWRzVGxGVVFraFJNVTU0VWpGT1NsbHFUa1ZWVlZaRFEydEdVbFpWUmtKT1JXeEVVa2hrUW1ReVpHNVRWWFJDWWpCc1JGRldSa1JrUkZwRVZXNXZOVkZzUlhwUFJGWXhXbFZ6ZUZreU9VbFRWMVZ5VFRCNGJWcHJPVXRSTURGcFlXNXdkRlpxV2tOT1JHdDZWMFZOUzJJeldUTk5WMFowVG5wS1FsSlVhSFpOYW1zeFlqSm9kR1ZGVm5KT01rWTBWMU00ZDFaVlZuUmtVemxKVDFWNGVGUldjSHBoUjFvd1VsaHdVVlJJUWtwUFYxRjRUbFJOTTFSNlVYWmxSWGcwVTFad2QxUkJjRE5YV0VaSVdURmtjMU14Y0hSWGJrNXhUWHBSTkZrd2QzSmtSWFJVVTFWak5Fc3hVa0pPVnpsRVpGUlNjbVJXUWpCT1YzZHlZa1ZHVUZwcVFYZGFWbWh0VTIxNFNsTlVSbEZpTURsTVRsWkNSR0pUZEVWRGEzZ3dVbXR3VjA1SWJFSmFSWGhwV1ZWM05WRlVVbkZYU0U1RldUQk9SbGx0VW0xVFdHUlJWVWhHVVdOdVVYcFpWbXN5Wkc1S1IyRjVPVVJoYldoSFZFZGFlazlGZHpKVlEzTjRXa2hyTTAxSVRuVmtSWE5MVGtWV00xVXdjRkpsU0dSeFZWVXhkMkl3T1VkV1JYQlFaREZSZVZwVVVtRmtibWhFWld4T2RtUjVPWEJaVlRWdlZsZFJNbU15YUROYVZsVTFVakExTkU0d1RUTmhWMGw0WkZac2JscFZaRXRYUlZKVFRsRndhVk5IU2pKVWVsWkRZVmRXYkZsdFNuZFRiVGt5VTI1T1dWVlZWbEJTVlRoNlpFZDBVbUZ0YUdsT00xRjJXbGM0TlU5SFduTlJWMlJzVjFkd05sZFZiSE5hVjFwd1ZHcFdXbFJyTlhWV01sVnlaSHBXTlVOdVRsTk5iVW95VVZaQk1WVXhSbGxYVjJSclRVVmFNRkV6U2xoVlYxWjBZekJHV1ZsV1drUmFlVGxhVFhwc1dFOVZWbTlQUkVaTlpWZGtXVmxyTlV4WFdHUm9XakJ3WVZOSFVqRlZibkJzVG01d2VHVkdiMHRYUnpGd1drZFplbFJHWkhCWk1WWklWVlpPY2tzeFpGVk9NbEpMWkd4V2NtVldTa2hpYkdSNFZHc3hVbEZxYkVoaU1YQjBUVmhDTm1OR1NtbGlNV3N6WW0wMGVHVllRalJUVlZwc1VtMDFNRlZIZUVkT1FYQkhWVmhPUldGcVVYcFZWWGd6VmpOc1VXSnVVa3hUUlZZd1pXdEtVMVJFYURSa1dFcHVWbFZLVDA5R1JURlVha0o2VDBoQmQwNVVVVEJhYTBaU1lXeEdUbFJzU21sWk1WSm9UVVZKTTJOclNrNVNSVXBxUTJ4T1RWcFZUbEJPVjJ4MFdteGtSRk15T1hoVVdFSnVZek5yTW1Sc2JFNVNWV015VXpCU1FrMUZaRzlOVjJSWlpVVmpORk42U1RSVE1tYzBZVWR3TUZJelJrWmFNMFp3Vkc1bmVXSlhOV2hNTUdkNVkxZDNTMVZHU25SVlJGbzJZVzV3WVZScVpFcFRNMk4zVXpCMFVVeDZUWGxMTUd4WFZWaFNVbUZVUWtSYVIxRXdWMGMwY2xJd09XdGtNbXhNVFZVNE1XUkhNVTFVTTA1cFdrVnZlRkp1VlhaT00yaHlUMVpTVDFKQmNGVmtNR3hGVVZaR1FsRnRPREJUVlVwVFlXdE9SRkZXVmtwa01GSXpWMVZTVjFWcVFsVlJWa1pKVERCS1FsWllaRUprTUZaRFRETndRbFF3U201VWJGcEpWVlJvUTFGWFdUUlNWVXBDVkZWT1FsVldiRE5EYkU0elYxVnNUR1F4YkVOUmJFWldVMFZHVWxKVlZsRmxhMFUxVkZWU2VsSXdUa1JqTUdSQ1ZWWldSMUZ1Y0VKUk1taHdUMWM1YTFOR1NqTlVNbXMwWkd4c1dWRnVaR3BsVkZaM1YydGtWMlJYVWtsVGFrVkxXWHBPVW1SV2EzbFBXRkpOVFRCd01sbHFUbE5sYTNkNVZXNXdhMU5GY0RKWmFrNVRZV3hzV1ZvemNFMWlhMFY2VjFod1FscHJTbTVVYkZwSlZUQXhSbEl3VWtKV01tUkRWa1ZXZDA0d1pISmFXR3cwWlVGdmNtUklXbTlWZWxaRFRWTTRORlZXV2xwVFZtUkxVbFZTUTFaVlNtNVViRnBKVlRCR1JsWkdVa05VUlRGQ1dqQmtRMkpYVmtOU1JVWkdVVEJHVlZGVE9VTmFNMDU1VVcxa1JsSlZSbHBVUjFwR1pEQldRME5yUmxWUldHUk9VWHBTU0ZFd1RucFNNRVpTVmxWYVEyUXdiRU5TYld4TFlqSlNTVlZ1WkZCaFZHZ3lWMVJPUTJWcmVIVlRibHBwVFRGR01GcFZVa1prVjBwSVZtcENhazFzV2pGWFZFNUxUbGRPU1ZWWVZVdFphazVMWW1zeFJXUXdaRUpOVmxaclUwaGtVazFWTVVWVVdHUk9XVlZHTW1Jd1RYbFNNSE41WVVSQ2ExTkZSVEpVU0dzMVlXMU9kR1F6Vm1oV01VcHpXVzAxVTJWWFVsbFVha0pOWWxVMU1sbHNUVFZTVVhCV1RWWktWRlpFUVRWV1ZrVjNVbXhzVGsxRk5WUldSVTB4WVcxT2RHUXpaRWxWVm14RlZteEpkMVF3U2tOWFZWWkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhRMnN4UWsxRlpFUlZNMFpJVlRCc2FVMHdVbEpTVlVwRVpERldRbEZVVWtwUmEwWlNVVlYwYW1Rd1NucGlSekF6VERCU2MxUkdSbmxrUkVwT1RsUkdkbEl6U2xSTE1qZ3dUa056ZG1WV1JuWlNSVnBYVWtWTlMwNVdaRFJSTTFWNVN6SkpOVlJHU2xGa01uUlVVMVZPU1ZkRk1ESmtNbFpwVW10a1MyUlhWazlPTTA1TFRqSTRNVmRHUWxoaFZ6bFlUbFprYzFORlJsSldWR1JJVG5wV1RFd3hSblpqTURGNVVWZFNWRlozYnpWVVZsWnVWR3hTVVU1VVNraFNWRWt3VTBWa1QyUkZlSEJOV0VaMlUydGFjMWt3VWpWalZrNU9ZbnBWTlZsWGFEVk5iVTVLVFc1R1ExSkZlRXhpTWtweVpVTTVTMDB6V2xoamJVWlhUVVpSTlZadVZraERiR1JFVkVWMFZWWnNhSEpaTUdSclpFaGtjMXByV2xOaGJYaERaV3BTZDFkWFkzaGhTRkowV21wV1dVNXJVbHBVZW1oQ1RrZHdlR1JxU2twaVJHeEZZV3hvUWs1c1ZsUlpiR040VW01d1dWVXdlSGxQVlRoTFlVZFZORmRVVWtwV01VMHlaREZyTTFsclRuSmhhMDVZVWtkT1UxVlZjRTVTVjJodVRucGFiV013T0hwa1NHaEdTekJhY0ZkWVNqRmpWR3hUVmxaa2IyRlZXWGhpV0d3eVRrWkZNbFo1ZEVSbFZVcEhVWGR3UlZwdVduZE9NRGxRVWpCR1QwNXRVa1pVTURBd1N6TkdVMDlZVG10aGJUbFVWMVYwUmxGdVFucGphbHBJWkVaQ1FsVllZekJhU0dzelRsUk9iRmw2VlV0TVV6QjBURk14UmxSclVXZFJNRlpUVmtWc1IxTlZUa0pXUlZWMFRGTXdkRXhSYnowS0lDQWdJSE5sY25abGNqb2dhSFIwY0hNNkx5OWhjR2t1WTJ4MWMzUmxjaTA1ZDJoNE5TNDVkMmg0TlM1ellXNWtZbTk0TVRRd015NXZjR1Z1ZEd4akxtTnZiVG8yTkRRekNpQWdibUZ0WlRvZ1pHVm1ZWFZzZEMxamJIVnpkR1Z5Q21OdmJuUmxlSFJ6T2dvdElHTnZiblJsZUhRNkNpQWdJQ0JqYkhWemRHVnlPaUJrWldaaGRXeDBMV05zZFhOMFpYSUtJQ0FnSUc1aGJXVnpjR0ZqWlRvZ1pHVm1ZWFZzZEFvZ0lDQWdkWE5sY2pvZ1pHVm1ZWFZzZEMxaGRYUm9DaUFnYm1GdFpUb2daR1ZtWVhWc2RDMWpiMjUwWlhoMENtTjFjbkpsYm5RdFkyOXVkR1Y0ZERvZ1pHVm1ZWFZzZEMxamIyNTBaWGgwQ210cGJtUTZJRU52Ym1acFp3cHdjbVZtWlhKbGJtTmxjem9nZTMwS2RYTmxjbk02Q2kwZ2JtRnRaVG9nWkdWbVlYVnNkQzFoZFhSb0NpQWdkWE5sY2pvS0lDQWdJSFJ2YTJWdU9pQmxlVXBvWWtkamFVOXBTbE5WZWtreFRtbEpjMGx0ZEhCYVEwazJTVzVrVUdJd1dtaFZWVTV1VDFWWk0wNVdWbXhTV0VwWVkydEdWbU5zUmpKWWVtUkVWa2hzVm1SWFJtcFdWVkpZVXpKR2RWb3dNVEJTVjAxcFpsRXVaWGxLY0dNelRXbFBhVXB5WkZkS2JHTnROV3hrUjFaNlRETk9iR051V25CWk1sWm9XVEpPZG1SWE5UQkphWGRwWVROV2FWcFlTblZhV0ZKc1kzazFjR0o1T1hwYVdFb3lZVmRPYkZsWFRtcGlNMVoxWkVNNWRWbFhNV3hqTTBKb1dUSlZhVTlwU21obGJsWjVXbGRPYzJSWVRqQmFXRWxwVEVOS2NtUlhTbXhqYlRWc1pFZFdla3h0YkhaTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1Fd3pUbXhaTTBwc1pFTTFkVmxYTVd4SmFtOXBXVmh3TVdOdFZtcGlTRlo2WkVkV2VVeFhTblppTTFKNlpFaEthR05ETVhwWlV6RXdZakowYkdKcE1YaGpibEowWkdsSmMwbHRkREZaYlZaNVltMVdNRnBZVFhWaFZ6aDJZekpXZVdSdGJHcGFWMFpxV1RJNU1XSnVVWFpqTWxaNVpHMXNhbHBUTVdoWk1rNTJaRmMxTUV4dE5XaGlWMVZwVDJsS2FHVnVWbmxhVjA1elpGaE9NRnBZU1hSWmJUbDJaRWhPTUdOdFJuZE1XRTVvU1dsM2FXRXpWbWxhV0VwMVdsaFNiR041TlhCaWVUbDZXbGhLTW1GWFRteFpWMDVxWWpOV2RXUkRPWHBhV0VveVlWZE9iRXhYUm1wWk1qa3hZbTVSZFdSWGJHdEphbTlwV1ZkUmVrOUhWVEphUkdOMFdUSlZOVTFETURCUFJFVXhURlJuTWsxWFRYUk9iVkpzV20xVk1rMXFZekZOUjFFd1NXbDNhV016Vm1sSmFtOXBZek5zZW1SSFZuUlBiazVzWTI1YWNGa3lWbWhaTWs1MlpGYzFNRTl0Umpaa1dFcHNXVEo0TVdNelVteGphbkJvWlc1V2VWcFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaEpiakF1Y0U1V05qY3lWbk50WkhKNVREUjViVkpUYlROR2FIRTBhbmhaTjNWVWJFRkdhWE5SWmpGalpYUXdiVTl4VG14SE9XbFRjRTlmVW5kbldXVjRkbEpWVmtodlEyZzRNSGcxZFVKaWVYTmhOMDVmZVZaQk9XTkVVa3hFVWpoSVZISkxkMXBtU0VkbFdGOUpiMk5UUm5wWE9VWnFVRmRDZWtabFdHODNOSEZrYmpRMFQwUnRZWEp5YzNsWU5EbEVaamRPZFhnNGQyUmlUelZ3TFdod2NFc3hNVTl1U3pWS2RrMXNWV0Z6T0ZCMWRVbDBUV2xOYTBOaFVtNTJWakZTVjB0b1dWUm9NRWR1Y25CYWRVbFNWRXhhVmw5c1ozcGtZM0JMVFMxamNuVTVZVEEzUzFkdk0wbHphRVF5V0V0VWF6QXlOSGcxVEZsd2FWcEVhRk5ZWlZkblYzSjJNSFV4ZURWc2EySTBhalZyU1VVNE5ERTVNMVJaT0ZKNWRVZzJSMnBPTFd0UlVVYzRlVTlLTWkxM1RWcGpUVkpVVDE5UWVuTk5TSEl6WjFNemEwTk1SRmMzTFV4SFMwaHRTR2RVVjFGeGRXbzFPSEE0VkY5QlJUaFFUelpJTW5NMmNVOUZaR2xQVnpoSVJHTlFMUzB0YjFaa09FMTZhMVZ1VjA1RGExRk5UeTFuUWtsS1p6QmFNVmh1VkhkZmVHZFJabGRRUzNSVVkyMU1RM2RMVEcxcllWTTFOVkJ5V1VwUlpsWm9kMjh5UlhST1dYVkJjWFl5ZVhaUGExZElja2hRVkhsV01UaENTVnAwV2t4elQyMTVVRjgzTW5BM2FqZDVkM05CZGpSb1pHdHVXVmt4ZUVOeVoybHFNWFp4YVVnNFkyYzFkVFpaY0VsaWJUWjRaa0ZDV0dwekxVNXphbDltU1RseFZ6aFlXRGRLVFdWMlUyOTZRbGd3TkZsVVkwRnZkemRWZVdkbWMycDRaemg2WW1sV01FZzFha2QzWjBGdGEyWjRWR3BDWDFkcVVWQllTVll4ZVcxbll5MU9UVXRmV1hoWlpVUlJjWFpCVFY5eE5YUmlkRWRNZHpkc1JreFliamgwT0RsdWNXTlZTa1JYTFdnNWQwa3RjVEZ1VG5kWGFuWXhhamhIT1V4elpsSTNWemg2WkZGeGFUZ3dSQzA1Umt0TmQyc3RjamxYUVhGR2VHaHNSbEVLIgoKLS0tCmFwaVZlcnNpb246IG9wZXJhdG9yLm9wZW4tY2x1c3Rlci1tYW5hZ2VtZW50LmlvL3YxCmtpbmQ6IEtsdXN0ZXJsZXQKbWV0YWRhdGE6CiAgbmFtZToga2x1c3RlcmxldApzcGVjOgogIGRlcGxveU9wdGlvbjoKICAgIG1vZGU6IERlZmF1bHQKICByZWdpc3RyYXRpb25JbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvcmVnaXN0cmF0aW9uLXJoZWw4QHNoYTI1NjpiY2M2ZDEyYmE0ZjFkY2Q3ZmEwMDg2M2YyODhlZDhiYzkxM2M2NjViYWNlYmFjNzliMzYwODgwZDFjZTMzMDUwIgogIHdvcmtJbWFnZVB1bGxTcGVjOiAicmVnaXN0cnkucmVkaGF0LmlvL211bHRpY2x1c3Rlci1lbmdpbmUvd29yay1yaGVsOEBzaGEyNTY6YTJmYmI0ZmFiMDA3MzU2M2I4ZWQyODk1ODU5Y2Q4YjcwNTgzNTM0MTk0YTYyMjI4NzExZTBjMzc4YTk1NjU5MiIKICBjbHVzdGVyTmFtZTogImF6dXJlY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
Error from server (AlreadyExists): error when creating "STDIN": customresourcedefinitions.apiextensions.k8s.io "klusterlets.operator.open-cluster-management.io" already exists
The cluster cannot be imported because its Klusterlet CRD already exists.
Either the cluster was already imported, or it was not detached completely during a previous detach process.
Detach the existing cluster before trying the import again.%                                                                                                                                                                                                                                        rgupta@rgupta-mac .ssh % ls
book-import	config		id_rsa		id_rsa.pub	known_hosts
rgupta@rgupta-mac .ssh % vi id_rsa
rgupta@rgupta-mac .ssh % vi id_rsa.pub 
rgupta@rgupta-mac .ssh % oc login hhttps://api.ocp4-wm6mx-ipi.azure.opentlc.com:6443
error: Not a valid URL: parse "https://hhttps:%2F%2Fapi.ocp4-wm6mx-ipi.azure.opentlc.com:6443": invalid URL escape "%2F".
rgupta@rgupta-mac .ssh % oc login https://api.ocp4-wm6mx-ipi.azure.opentlc.com:6443 
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.ocp4-wm6mx-ipi.azure.opentlc.com/oauth/token/request
rgupta@rgupta-mac .ssh % oc login --token=sha256~Bt3UDxQC_RASoq8W3FCS4_50BRnWrr9RtdWAWrRJOww --server=https://api.ocp4-wm6mx-ipi.azure.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.ocp4-wm6mx-ipi.azure.opentlc.com:6443" as "admin" using the token provided.

You have access to 73 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac .ssh % >....                                                                                                                                                                                                                                                                      
azU1WVdzeFQyUnNWbEZhZW14aFpHcHNhMVp0ZUc5VWJsSmFVek5zZDFsWVVtdFdSbFpWWTBoU2FFTnJTWGxVUmtwVVVXMU9WVkZyWTNKa1JrbDNUbXBTTmxZd01UVk5ibHB3VW0wNWNHTlVRbkppZWs1RlltbDBORlZFU2xWaVIxWjFWMGhHZVdGclZsZFJNalZIVFd0NE0xcFljREJUTW1SMFRXMWtjR0pyVlV0amEyeEVaRVJPVEdWVlkzWlNiazVUVXpKb1JWWlhWbGRYVkRCTFRGTXdkRXhUTVVaVWExRm5VVEJXVTFaRmJFZFRWVTVDVmtWVmRFeFRNSFJNVVc5MFRGTXdkRXhWU2taU01HeFBTVVZPUmxWc1VrcFNhMnhFVVZaU1JreFRNSFJNVXpCTFZGVnNTbEpyV25GUk1FNUNaR3BhYmxGWVpFcFJhMFp1VTFaS1FsTnJWbmxSTUZaNVZVVlNRMkZYTlZaTU1rcFlWRWRzV0dKc1ozaGlNMlJGVlZac1MxTXlPV0ZUVjJneVdUQTFRbFZWVmsxUmJFWkNaSGR3VldWclZrMVVWVVp5VWpCRmVGWlZWa05oUlRGRVZteGFUbVZGZEZWUlZ6VkRXakExVjFGclJuWldSV3hHWWtoV2ExSXhXalZaYlRGWFRVVnNSMVJ0ZUZwTk1WbzFXVlpvVTA1VmJFZFRiWGhxVFd4YWIwTnRUblJVYlRsS1VsZFNOVmxxVGxka01ERlRWbGhrUm1ReGJFVldiRVpTVWtWV00yVkZjRlpOVlhCSlUxVmFTMlJ0U1hwVlYyUllVa1ZXTTFOSGFHcFVhekZ4VVZoa1VGWkZSWGRVVlZKQ1pEQXhSVkZZWTB0V01taHFWR3N4Y1ZaWVpGQldSVlY0VkZaU1dtUXdNVVZSV0dSWVlXdEdOVlJXUm5wa01FNVNWMVZTVjFWV1JraFNXR1JMVm14V05sSldaRTVSYkVaSVVWUkdWbEpWVG05VVZUVlZVakZaZDFOcVRrNWFkM0JUVm5wV2NWa3lOWE5rTWxKRlVsVjRUbEZYZEVoUlZFWldVbFZHTkZSVlRsWmhhekV6V2pKa1JtRlZNVUpOUldSRVZUTkdTRlV3YkdsTk1GSlNVbFZLUWxWV1ZrSlJWRkpLVVd0U00xRllaRzVhTUZaTVEydEdkbE5WU2tKVlZVMHpVVmRvVm1JemNGRlpWMlJ6VkdzeFVWSllWalZVYkZwaFZFVlJjbE5WZURSaVYwWmhUbXhHZG1GWE5WbFZNa1o0WkVaT01VNVlhRlpsV0doNVRrUldlVXN4YUZsVFZ6ZzFXVEZCUzFWcVZsSldWbHBWVm14b2NWTnFXblppTW5CeVYycHNXbE5VYUZKalYzaFFXVzVhVms0elpEVk9Na3B4V1RCT00xZEdRazlYYXpsUVdtNVNOazF0TlROV01tUjZXVzVhZWxFeFZrdFJNV1JKU3pKd2EyVkJjSHBsUmtKMVUwVjBObUZITUhKTU1ra3hVa2hTUjFaWGRGaFdNMFpxVW14U05tRnNVa3BXV0ZVeVRWaEtNVTFzUVhwaVZVb3pUa2hHVjFaWVJUTlhibEpGWTBkV2MxVlZVbE5qYTNNMVZIcG9ZV1JZVW5SRGF6VkpaV3BhYUU1SVZsRldibXgwVjJsMFJWRldhRmxaYmtJMVdXazVNVkZ1YUdoTk1VNXZZa2RqTlZKcWFHMWlhMDVwWkc1b1RFd3lWa2hOTURGSldWZE9WMDB4VmxOa1ZrSk9ZMnhPV1ZGdGJFMWxSMk5MVjJwT1YySllUWFpTVm1zMVRtdHdhazVYZUZGTU1EbDJZVlJLVTA1c1ozWlNXR2h4WTFjeFFtSkVUbEZPVkVaVlN6Sk5ORkZxVm0xV01qRnFVVzFPVm1OcVNsQmhlVGd4WWxod2NrNVVUbXBXVkZwcVVuZHZkbUV5YkVkVFIwWkhZMGhLY0ZacVJqRmxSa0pPVmxka1VVMVVaRmRTTW1od1QxaE9WMUZYWkU1UmEwWkNVakp3Ymxvd1ZrcFVWV3hLVVd0S1JWRlZPVU5hTURWWFUwWkZORkZyUm0xUFJWWkRVVlV4UkVOclJscFhXR1JKVlZac1JWWnNTWGRpUlVwRFYxaGtSMUZXYkVwVE0yUmFVV3RLVWxaVmFFSmtNR3hJVVRCT2VsSXdSbEpXVlZwRFpEQXhRMVJWU2twU01FVjRWbGRTUm1Rd1ZrTk1NMlJTVTFVeFFsZFZTVXRSVjFrMFVUQkdVbEZZWkVsVlZteEZWbXhKZDFRd1NrTlhWVlpIVVd4R01XTXphR3hOTVdSSFdXdDRlV0pGUmt0VlZUbGFXbTVKTVUxcmVFZFVWWGhJVkZWSk5GSXdSWGhXVjFKS1pERkdXbFJWU21oUlVYQkhVMGN3ZDFZeVZtRk9NMUl4VjBkMFFsZEZPVUpSTUd4eFUxVmtjMkZxU1RKWGJsSXhWRlZTU2xJd1RrUmpNR1JDVlZaV1IxRnVaRVpSYTBwRVYxaGtTMUpGUm5CUmJXUnVZMnRLYmxKVldrTlZWMDR6UTJ0R2RsZFdaR2hUUmtsM1dUQlNkbVJyZDNwYU0yaE5ZbGQwTVZsclpGZGtWbXQ2VTFoV2FVMHdjSFZVU0hCQ1ltdEtibFJzV2tsVmFtaEdVMVZTUWxwVk1VTmxWMlJJWTFWR1dtRkhhR0ZpTWxKSlZXNWpTMVF5YXpSa2JWWkZVbGhXV21WVVZucFhiR014WVcxT2NFNVlXbXBpVjA0eVZGVk9TbEl3UlhoV1YxSktVVlpHYVZSVlNuSmtNRTVDVjFWa1lVNUZWazVSVmtaS1VXc3hRazFGWkVSbFdFNUlVVlpHVWxGbmNHNWtSR2hWVVZaR1JsRnJNVUpOUldSRVZUTkdTRlV3YkdsTk1GSlNVbFZLUkdReFZrSlJWRkpLVVRCR1VsRXdXalZoZWxaSlZVaEdVVTB5YUZaVk1Gb3lWR3hhZFZwVmVFeFhWbXN5VFZSR1ZWVnFXbGhEYkVKVlZHMTRhbUpHUmpCYU1rWkZZMWhqY2sxNlVrcFVSR3h0Wld0NGEyUXdSazFhU0ZaUVRERndiR0pGTkROaE1HeExTekl3TTA1SVZqVlJVM1JzWVZoU1UxZFVhSEpaZWxsM1RqRlNjbEY2Vlhwa01uZExZVmQwYldKV2NGaE9RemxUWkd4U1lVOUZNREpXVlhOeVRsWldObUZGY3pSaGEwNXJWRWhXVGxJeGJFMU9hM1F5Wld4b1NGVnNUbTVoVkU0MVZFZGtjVnBZWkZKa1JVNVJZVEJzVjJWcVdrVk5iRVpTWldkd1JHRXlUbTlhVlVaMFVUQnZORlJZUmpWVGJsVXhaVzE0Tm1WV2NFNWhhMFl5WW0wMVFsWkVVVEZrUmtwQ1pVZFdjbU51VGpGUFZGSjZWVlJTYkZveVVsTlJNalZwVmpGT1JXUkdhek5oTW1keVVXdHNkRU50ZUV0VWJHaDJVV3BHYzFGck1VWlRNR3g0VGtaR1JWWlZPVmxpTVVwdVdtMWFNVkpIWkc5aGJWVjRWak5LU0U5Vk1VMUxNR2hwWVZoT2VFd3piRWRVTUdRelYwVlJOVlZ0YkZsUFJWa3lZek5qTWxaNlVVdFpXRnBDWkZoYVJXTXpjREZhVkZaTlRUTk9OazlFVmt4TE1GWkVUa1pyZG1Rd1dsZFNSVFV5VjIwNE1GWkdiRmxaVnpneVYycENiVXN5ZUZKVE1rMTNaRVJvUlZWV2JEWmhla1pRVjBaYU1VOUlTbmROWjNBMVUyc3hSRTV0Um5OVVIwcERXbXM1UlZGVmVHRmtiR3hKVGpJME0xcEhPSGhSVm5CelkzcFNTazlYVVhoVlJGSnhZbTEwUldOc1JuWmxSVWw2VmxoR1VrOVhhRmRpUkU1TlVsVjBVazU2VGpSU2FrWlFRMjVzVEU1VlpHOVNSVkpaVDBjNVYxcHJaRXhTYWxZeFN6SlNiRmt3YkhwVFJGSmFXVlpTTTA0eU1WRk5NR1JIWlVWd1ZHTllXWHBMZWtKelZsVmFTMkl5YXpGVVIwMHhXa2RGZUU1RWJIZFBWRUpLV2toTlMyRkZUa1psU0VwMlZFUkZjazR5TVhsbFZXeHlWMFpDYkZKck1ERldSMlJRVDFoSmQyTnVXbUZaVlVwSFZETmFWMDF1YjNkYU0wRjZUbFp2ZDBzd2R6QldNVUp6V1c1V1JtRnJOSFppU0doUlVtMXNkVXQzY0VsaVJsWnhZMnBvYmxWdVRrcE5NMFp0VTJzNVVsSnVhM1pQV0VwTVUxVndVMDFHYTNaUFJUbDBaRE5SZGs5SE9WVldNbVExVFZjeGExcFZhSFJpVjNCeVRqSnZlR0pzYkhwa2EwMDFVMnhPVWs1c2NESkRhekZ6V2tkNFZWWkZkRU5OTTNCdlZrZG9WMDFUZEZsV01XeDNUbTVLY1ZwRVZrdFdla1kyV1d4YVdGSlhkRTFVYm1oR1RqQmtTMVpIYUVaV1ZXTjZZek53YmxGc1draFZSR1IzVlRGa1ZWWldVbnBqVm1kTFltdDRVMWx1WkVsVU1qbDRUakpvU1dReVl6bFFVVzkwVEZNd2RFeFZWazlTUTBKRVVsWktWVk5WV2twUk1FWlZVbE13ZEV4VE1IUkRhVEIwVEZNd2RGRnJWa2hUVlRSblVUQldVMVpGYkVkVFZVNUNWa1ZWZEV4VE1IUk1VWEJPVTFWc1IxZFZVa1JSTUVwR1lWZGtRbVF3YkVOUlYyUktWVlpHUWxKcVRrcFdSMXBXVG14V1RFNUVaSFZaV0VaUlVqRkdUR1JJY0VKVWEwcHVZVE5HYjJFeWJFaFBXR04zVVd0R1VtTXdXa0pTUlVWMlEyc3hWRlZZWkVwYU1XeEZWbXhHVWxNd1ZqUmtSVlpvVmpKU2QxcEZaRWRqTUd4SFZHNUNZVTFxVm05YVJXaFhaVlp3VkZGc1ZtcGliRm8yV2tWT1ExSkhTalZPU0doSFpXdEdWMUZ0WkU5V2EwcENWRlpSUzFKSGRGTldSbHBFVVd4T2FVMXFhM2RUVlZaUFVXdHNSMW96Y0U1UmFsSlpVa1pTU21WRk1VVlNXR3hPVWtWVk1WUldVbEprTURCNFlqRm9SVlpGYTNkVVZWSnlaV3N4UlZKVVVrNVdSa1l6VkZSR2RtUjNjRlZsYTFaTlZGVkdjbEl3UlhoV1ZWWkRZVVV4UkZac1drNWxSWFJWVVZjMVExb3dOVmRSYTBaMlZrVnNSbUpJVm10U01WbzFXVzB4VjAxRmJFZFViWGhhVFRGYU5WbFdhRk5PVld4SFUyMTRhazFzV205RGJVNTBWRzA1U2xKWFVqVlphazVYWkRBeFUxWllaRVprTVd4RlZteEdVbEpGVmpObFJYQldUVlZ3U1ZOVldrdGtiVWw2VlZka1dGSkZWak5hTW1SS1lWVXhRazFGWkVSVk0wWklWVEJzYVUwd1VsSlNWVWxMVVZaR1ZsRlZSVEJUVlU1RlpEQkdNMW95WkVwVE1FWjJVMVZPUWxWVlRqQk9hMDVUWldwc1ExVlVUVFJPV0Zac1UzcEdhbUl3YUVwYVUzTjZWRWRhYlZRd2NFUlVWMHB4WlcweFYwNXJTVEJQVkU1WlVYZHdkbVJxWTNoWlZ6QXpUV3RHUms5SE9IbFBWRloyWVVjeE5GSlhjek5aV0doYVRIcENWbEpYTVRGTU1HYzFWRWhHVGxkdVRtOWFibEpHWld4Q1RXTkZhelZhUkVVeFRYcGtVRTVET1RSVVNHaEtWMjVDVFVOdVpGcGpWV1JxVmpKNFRGZHRNV0ZqTW05NlRrUm9hbFJEZERCVE1VNUtVbnBuY2xaRlJURmlNRTR4VGtkME1WVklVVEZpUTNSelVWVTViVTFFUW14WFIxcExZa1ZzU2sxV1FuWlVNSE14VlVWT2RFc3dVVXRVU0ZKSFUyeFpNR1ZWUm10VVIwcG9WRVJzUWs1SGNGbGpNRkpxVVRCV2FWcEhXa3BrTVVKUlkxWkNlV1JFVG1oWFZGb3lZMnRhY2t3d1RuRmhSVnBOV201Tk5GUkVXbEZMZWtaclpWUmpkMk15TlRCVGQyOHdVbGhrVkZOc1JqUmtNbkJTVkZoQ2RsUXdXbFZUYXprelZrUktiRTVHY0RKbFJVNDJWVEk1TTB3eWJHaFViV2hXV2tSYWVtRklaR3hXVkd4SVZHNW5NMUY2WkhCWmFrWXhWMWRrYkZJd2NGbFNSa2t4UTIxS1NWbHVXbEJPVlVwd1dsZFdhVmx1UWt0aU0xcExZekZvVWxKVk9VWlVlazR3WVRGR2NXRkhTVE5rUXpsc1lucHJORnB0ZUVKYU1sWmFZVzV3V2xOWGVHeGFiV3hQVGxac1QxUnROVmhhVTNRelRsaHJTMk14U1hsWmJscENWVVJXVkZWV2FGcGFNbEYzVW01U1JHTnNaRkphVnpGNlVWWm9hRlpyVG01TU1XdDZUMVpqTlZKWFp6Uk5WWGcxV2pGb2FWUnJkRnBrTWtadVUyeHdTVnBJVmxObGJWVXlaVzVHTkZkbmNGbGlWMnhyV21wT1RWWXliR3BXVldSU1ZUSnpjbFl4VVROYVJYQXlWbGQwTlZWclpIVldNMFpQVkZaR1EwOVZaSFpYYlRCNFkwaHdkMVZ0U25aWFZHUjFZbXBHTldOSWFFcFNiVlpIWW01U1VXSkZXVEJEYTFwU1l6QlNjVTVFVGxKVVNHUllaVlpDZFdSRmRFbFNXRkkyVVd4S1RVOUlhREZqYldSV1VXczBORlZVVms5TlNFMDBZMFJCTVU1RVVtMVJWa1p4VlZVeFQxVnRTbXBXUjBWM1VXcGtlVkZyTVVWUmJVMUxWVEI0YkZFd09ERmhWekZ0VmpCT1RHSXpSazVqUjJSNlpWUmFNbGRWTVVaU2VscE1Va1ZGZDFJeVozaGFNV2cwVW5wb1RFMXFhRXhoUkdodllXNVNTR05WVm01alYyeFBaVVJLZEdKdFJYWlRSRXA0WWtGd1VWVnRNVkZPYm5CeFpXeHdUMDR3YkV4a2VrSk1VekZCZGsxNlNYSlRWbHBTWkVaR2NFMUZUbXRhUkZKWlltbDBTRlF5VWpOaFZYTjRWSHBXTUdKVmVGQmpNa3ByVTJwR1IyUlRPRE5sUjNNMVZrVTFSVU5zVWpOVFZWSkNWVlZHUTJKNlVrcFJiRXB4VVRCT1FsWlZiRE5TU0dSYVVrWmFVMDFHVWtKVlZXZDJVV3RHVm1Rd1JqTlNWVWwyWld0R1VGRnRaRTlXYTJoU1QwVktRbHBxYUVaUmEwWk9VVEJHVWxkWVkwdFZNMlJhVTFWME0xZFZTa05WVmxaSlVWWkdSbEpXUWpaUlZHeE9Va2hPU0ZFd1RucFNNRVpTVmxWYVEyVnJSa1JoUjJzMVlqSlNTVlZ1WkZCaFZHZ3lWMVpvUTJReVRqVk9XRUpoVWpGYU1WcEZhRXROVVhCcVRURkdNVmRVU1RWa1JYZDZVMjVhYVUweFNqWlVSRXBUWlcxU1NWTnVXbWxOTVVweFYxWm9ibVZyZUhWUlZFNWFaV3RHYlZGdFpFOVdhMmhVVkZWV1NGSkZSbGhhTUVwVlVsaEJNMUl5ZEd4bFdHZzBRMmwwTUdSdGFGUk9WVWw0VEhwb1VsWnNiRXBXTUhCR1VrVktWbEZ0WkU5V2EyaFVVVlZXVlZaRlNrMVVWVVp1VWpCS2RGcFZTa1ZSVlZaRVVWWlNRa3d3U201ak0wcERXakJXUmxGV2JFMWFhMVl6VWxWSlMxRldVa0prTURGRVRrVmtSRkV6VGtoUlZrWldVbXRLTTFOVlNrZGhWWEIyV2tWb1UyUXdPWEJQU0ZwYVRUQktObFJITlV0a2JVbDZWVmhTYkZKRlZqRlphMlJYVFVkTmVWWnVWbHBOTUc4eFdUQm9VbVJSY0dsTk1IQjFWRlZTTTFJd1JYaFdWMUpKWkRGRmVGUlZVazVrTURGb1VWaGFkbEY2U2toVGVrcHZUVWRTU1ZGVVdrMWxWR3h4V1RJeE0yUlhSbGhWYlhocFlteEtOVnBHYUU5TlJYaDBWRzVhYVZWNmJFWkRiRlY0Vld4T1ZVMUViRlpWVkVKSFYxVXdkMVJzVGxWUmVsWnhXVEl4TTJRd2FGSlhWVkpYVldwQ1VGRnJTbHBTVlZwSllsUkNXRnBXYnpOa1NGWlpZVEJHV1ZRd1JrUlRWM0JLVWpKNGNVMXFXbUZrU0ZWTFZGVkZkMUl3VGxSalZXUlVVMWRKZWxKR1JrWlJhMDR6VmxWR1FrNUZiRU5SVmtaQ1V6Sk9NMUZ1VG5OaVZHTjJVa2Q0VFZWWVNqQk5hekF4VFZjNVNHTnNUWEppZWxFd1MzazVOVlZYT1VWU2JGcEZVWGR2TVZZemFFUmtWRWx5V1dwc1RWVnNRak5oTVU1S1VUQm9XVlJVV2pOYVYwcEhVakJ3TVZwVk5ETmpNRzh6WW5wV1dWVkdaSEJpTVdNeFZqSjRTVkZXUmxaT01HTXpUbFZ6ZGxWWE9YcFVXRXBDV2taT1dFTnFiRTVXVjJSUFZrWkJNVTFyWkVaTmFsSkpVakExTUZSSGEzaGpWemxMVW0xNGFsSkliSGhWTURGMlRsUnNhR0ZJYTNsWk1HdDVZMVZLUlZSRmRIWlpiWFEwVERCdmVtUnNaSGxaVmxsM1ZrUnNWMlJWWTB0V01FNU5VekZTVjFkSGRHcFNNbEl3WkRKNGJWSnNTbkZpUlVvMlRraENXbHA2Um05a1J6RnRUbFpuTWxKR2JGQlBSVVV3WVc1R01rMXJiSE5QVlZKeFYwVkZNbFpXVG1sV2VrWkhaV3hvVkZSSVNUVlVkM0J2V2xSb1drNUZiRmhWZWxvelYxUmthVkV5ZEhGUk1XUkZXVEZLVWxOck1VWmhSMk16VG0xYWVsUjZUakJsUlZWeVVtMXNXbU51Vm5oUFZrcFdWakpvY0ZKcVJuUmxXRmt3VlZSYVdFc3dUalZSYTFwRVEydFNiV1J1UVROVU1EbElVVlUwTWxwRlZsQlVWRkZ5WTFaSk5XTXlVbkZpTVU1YVV6QldRMk5JVG5sT2EyUXdWVVZHVW1SNlVtdGxWR014VFRKV2FrNVJiM1JNVXpCMFRGVldUMUpEUWtSU1ZrcFZVMVZhU2xFd1JsVlNVekIwVEZNd2RFTm5QVDBLSUNBZ0lITmxjblpsY2pvZ2FIUjBjSE02THk5aGNHa3VZMngxYzNSbGNpMXFlbVI0ZUM1ellXNWtZbTk0T0RNd0xtOXdaVzUwYkdNdVkyOXRPalkwTkRNS0lDQnVZVzFsT2lCa1pXWmhkV3gwTFdOc2RYTjBaWElLWTI5dWRHVjRkSE02Q2kwZ1kyOXVkR1Y0ZERvS0lDQWdJR05zZFhOMFpYSTZJR1JsWm1GMWJIUXRZMngxYzNSbGNnb2dJQ0FnYm1GdFpYTndZV05sT2lCa1pXWmhkV3gwQ2lBZ0lDQjFjMlZ5T2lCa1pXWmhkV3gwTFdGMWRHZ0tJQ0J1WVcxbE9pQmtaV1poZFd4MExXTnZiblJsZUhRS1kzVnljbVZ1ZEMxamIyNTBaWGgwT2lCa1pXWmhkV3gwTFdOdmJuUmxlSFFLYTJsdVpEb2dRMjl1Wm1sbkNuQnlaV1psY21WdVkyVnpPaUI3ZlFwMWMyVnljem9LTFNCdVlXMWxPaUJrWldaaGRXeDBMV0YxZEdnS0lDQjFjMlZ5T2dvZ0lDQWdkRzlyWlc0NklHVjVTbWhpUjJOcFQybEtVMVY2U1RGT2FVbHpTVzEwY0ZwRFNUWkpibXhzV2pGS1RWcHFTbFpVYlVvMVZrYzFXVmd3YUZWbFYxWnBUbFprUjA1RVFraE1WbWh0VDFWU2NWWXdXa2RQUjNBelVXeGtTMDF0YzJsbVVTNWxlVXB3WXpOTmFVOXBTbkprVjBwc1kyMDFiR1JIVm5wTU0wNXNZMjVhY0ZreVZtaFpNazUyWkZjMU1FbHBkMmxoTTFacFdsaEtkVnBZVW14amVUVndZbms1ZWxwWVNqSmhWMDVzV1ZkT2FtSXpWblZrUXpsMVdWY3hiR016UW1oWk1sVnBUMmxLYUdWdVZubGFVekZxWWtoV2VtUkhWbmxKYVhkcFlUTldhVnBZU25WYVdGSnNZM2sxY0dKNU9YcGFXRW95WVZkT2JGbFhUbXBpTTFaMVpFTTVlbHBYVG5sYVdGRjFZbTFHZEZwVFNUWkpiVVkyWkZoS2JFeFhUbk5rV0U0d1dsaEpkRmx0T1haa1NFNHdZMjFHZDB4WVRtaE1XRkoyWVRKV2RVeFhUbmRrUjFreVNXbDNhV0V6Vm1sYVdFcDFXbGhTYkdONU5YQmllVGw2V2xoS01tRlhUbXhaVjA1cVlqTldkV1JET1hwYVdFb3lZVmRPYkV4WFJtcFpNamt4WW01UmRXSnRSblJhVTBrMlNXMUdObVJZU214TVYwNXpaRmhPTUZwWVNYUlpiVGwyWkVoT01HTnRSbmRNV0U1b1NXbDNhV0V6Vm1sYVdFcDFXbGhTYkdONU5YQmllVGw2V2xoS01tRlhUbXhaVjA1cVlqTldkV1JET1hwYVdFb3lZVmRPYkV4WFJtcFpNamt4WW01UmRXUlhiR3RKYW05cFRrUk5kMDFVVlRST2JVMTBXbTFOTlU1NU1EQmFSRkpyVEZSbk0xbHFhM1JaZWtKc1RucFdhMDVIVFRCUFJHc3dTV2wzYVdNelZtbEphbTlwWXpOc2VtUkhWblJQYms1c1kyNWFjRmt5Vm1oWk1rNTJaRmMxTUU5dFJqWmtXRXBzVEZkT2MyUllUakJhV0VrMldWaHdNV050VlhSWk1uZ3hZek5TYkdOcE1XbGlNamt3WXpOU2VWbFlRWFJqTWtWcFpsRXVRVmd6UW1GRGJ6bEtjR0l6Y3pKU2FqaDJlRU5rVVdNd1JtMXZkMWx4WkdkbVlXNXdibWxTU25GalVFVk1jRlprWkhWaVYwaE5MVWRHVUVSWVJWcFNUa2RZUzBRMmJsZ3pkM0pyYUMxWVFVMVZWWE5PTVVaTFpUUXlVVzFNWkU5amQwTlhURTFJVTFSdFEwVkxZbTR3WDNWdFJXSmZSMVpPV21aaGJsTjVZVEZTZGtKVlUzcFZlRzVDYVhaQ05HaDNMVVJJVEVwUk4yZHNYMEZrV1hoNk1WUkVTR1YxUTJNdFRUVkJhR0ZsZUZwUk1uZzVXbTFETTBWc2RIUTRMV3hOVXkxd1lXcElUVXB6T1d3dGRVdGZjV3BTWlVWVVJqTlhaMDFaWTFSZk4wSktUR0ZxYW5VeVVuUndNMkZ1UkZaYWQwRlJXV2w1UVRkMk0xOUViVzFJYTNCc1JsUk5iMHBTUnpSRVRXVmxka2Q0Y2tseVUwdElaVU4zVTJscFZFMVFaMWh6VjFkcFVsOW1Tbk52YW5oaFltNXVhMFI2ZGtkNGIxWm1Oa0l3UmxoRE1FeEdUbFpFV21rMFZVTkRaM1JVY2tKTmJUaHFabE5PZHpCV0xWcHlSMUV6Vm1WU1FrVkVlRXB2V0doUWFtSlZOMWt3UWxSelJWcFVjV2t4Y0dkblVsSm1Oa2huYTBkQmVFWjFXbVUyV214U1lXaFdUMmxrWVUxR2QzcENZMjFHVFdoVU1YbEtkbUp6VVRnMlRtTlRZVEJ3ZDIweVZWb3lURmwyVFVsMVExOTNUMmRhVEd3emRFOHhhVlp4ZFZCTVl6VnBVRVJhUTBWUFkxTldZWFZ1U21oZlNsZ3dUVFp5ZVdSb2QwRm5OV1k0U3pWQlRFUTJXVWRpTUVWSlgxTTBiak01TjFOclpqaGllSFpwZVUwNFRFcGtTMjFKUldoR2EwOHhZVEZZYWs5alRsTTVlV2w2UW5Cc1RrUnljbUk0T1c5NE9HNU9URmRwYnkwMFUzcGxWRW96V2t3NWVsQlFjMU5CUTBodmRGRktNekIyVWxGRVdVUTBlWGxCV1ZwUGRETXlhblpKVlZwUlJqbDROMEU0TjNseUxUUjZVR2xLTlZwV1lUbGhUR0ZKVVRORFZuZEVUR1ZSZWsxVWRHSXdhbU41UkhsUlpIcHBhekpUU1hKdGVsZFlZMWw1VW1aS1dEQUsiCgotLS0KYXBpVmVyc2lvbjogb3BlcmF0b3Iub3Blbi1jbHVzdGVyLW1hbmFnZW1lbnQuaW8vdjEKa2luZDogS2x1c3RlcmxldAptZXRhZGF0YToKICBuYW1lOiBrbHVzdGVybGV0CnNwZWM6CiAgZGVwbG95T3B0aW9uOgogICAgbW9kZTogRGVmYXVsdAogIHJlZ2lzdHJhdGlvbkltYWdlUHVsbFNwZWM6ICJyZWdpc3RyeS5yZWRoYXQuaW8vbXVsdGljbHVzdGVyLWVuZ2luZS9yZWdpc3RyYXRpb24tcmhlbDhAc2hhMjU2OjU5MWYyMjYwNjdmNDFiZjZhZDQ1MjU5MThlNWE2MmMyZTFjMDY1NDkzNTIzODNiYTZkZjdjYTBlMGRhOTUxYTMiCiAgd29ya0ltYWdlUHVsbFNwZWM6ICJyZWdpc3RyeS5yZWRoYXQuaW8vbXVsdGljbHVzdGVyLWVuZ2luZS93b3JrLXJoZWw4QHNoYTI1Njo1YWM2MGJhODg5NDgxM2QxNDJiYTgxYWQ0NjlmMGIzZDhmNTEyNjY4MTRlYTdiNjJkYTcxZjNhNzFmN2Y3ZWIwIgogIGNsdXN0ZXJOYW1lOiAiYXp1cmUtY2x1c3RlciIKICBuYW1lc3BhY2U6ICJvcGVuLWNsdXN0ZXItbWFuYWdlbWVudC1hZ2VudCIKICBub2RlUGxhY2VtZW50OgogICAgdG9sZXJhdGlvbnM6CiAgICAtIGtleTogIm5vZGUtcm9sZS5rdWJlcm5ldGVzLmlvL2luZnJhIgogICAgICB2YWx1ZTogIiIKICAgICAgZWZmZWN0OiAiTm9TY2hlZHVsZSIKICAgICAgb3BlcmF0b3I6ICJFeGlzdHMiCg==" | base64 -d | kubectl apply -f - || echo "VGhlIGNsdXN0ZXIgY2Fubm90IGJlIGltcG9ydGVkIGJlY2F1c2UgaXRzIEtsdXN0ZXJsZXQgQ1JEIGFscmVhZHkgZXhpc3RzLgpFaXRoZXIgdGhlIGNsdXN0ZXIgd2FzIGFscmVhZHkgaW1wb3J0ZWQsIG9yIGl0IHdhcyBub3QgZGV0YWNoZWQgY29tcGxldGVseSBkdXJpbmcgYSBwcmV2aW91cyBkZXRhY2ggcHJvY2Vzcy4KRGV0YWNoIHRoZSBleGlzdGluZyBjbHVzdGVyIGJlZm9yZSB0cnlpbmcgdGhlIGltcG9ydCBhZ2Fpbi4=" | base64 -d
customresourcedefinition.apiextensions.k8s.io/klusterlets.operator.open-cluster-management.io created
namespace/open-cluster-management-agent created
serviceaccount/klusterlet created
clusterrole.rbac.authorization.k8s.io/klusterlet created
clusterrole.rbac.authorization.k8s.io/klusterlet-bootstrap-kubeconfig created
clusterrole.rbac.authorization.k8s.io/open-cluster-management:klusterlet-admin-aggregate-clusterrole created
clusterrolebinding.rbac.authorization.k8s.io/klusterlet created
Warning: would violate PodSecurity "restricted:v1.24": allowPrivilegeEscalation != false (container "klusterlet" must set securityContext.allowPrivilegeEscalation=false), unrestricted capabilities (container "klusterlet" must set securityContext.capabilities.drop=["ALL"]), runAsNonRoot != true (pod or container "klusterlet" must set securityContext.runAsNonRoot=true), seccompProfile (pod or container "klusterlet" must set securityContext.seccompProfile.type to "RuntimeDefault" or "Localhost")
deployment.apps/klusterlet created
secret/bootstrap-hub-kubeconfig created
klusterlet.operator.open-cluster-management.io/klusterlet created
rgupta@rgupta-mac .ssh % oc login https://api.cluster-jzdxx.sandbox830.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-jzdxx.sandbox830.opentlc.com/oauth/token/request
rgupta@rgupta-mac .ssh % oc login --token=sha256~u8LYAAC__cnLfPSP4rMiLk5pAEuxaWbzT7VonaQKTEk --server=https://api.cluster-jzdxx.sandbox830.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-jzdxx.sandbox830.opentlc.com:6443" as "admin" using the token provided.

You have access to 82 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac .ssh % oc get nodes -o wide
NAME                                         STATUS   ROLES                  AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                       KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-129-192.us-east-2.compute.internal   Ready    control-plane,master   26h   v1.26.5+7d22122   10.0.129.192   <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
ip-10-0-144-107.us-east-2.compute.internal   Ready    worker                 26h   v1.26.5+7d22122   10.0.144.107   <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
ip-10-0-150-55.us-east-2.compute.internal    Ready    worker                 26h   v1.26.5+7d22122   10.0.150.55    <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
ip-10-0-231-248.us-east-2.compute.internal   Ready    control-plane,master   26h   v1.26.5+7d22122   10.0.231.248   <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
ip-10-0-231-253.us-east-2.compute.internal   Ready    control-plane,master   26h   v1.26.5+7d22122   10.0.231.253   <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
ip-10-0-253-70.us-east-2.compute.internal    Ready    worker                 26h   v1.26.5+7d22122   10.0.253.70    <none>        Red Hat Enterprise Linux CoreOS 413.92.202306141213-0 (Plow)   5.14.0-284.18.1.el9_2.x86_64   cri-o://1.26.3-10.rhaos4.13.git994242a.el9
rgupta@rgupta-mac .ssh % clear

rgupta@rgupta-mac .ssh % oc whoami
Unable to connect to the server: dial tcp: lookup api.cluster-jzdxx.sandbox830.opentlc.com on 192.168.86.1:53: no such host
rgupta@rgupta-mac .ssh % oc login https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-hk6cl.hk6cl.sandbox338.opentlc.com/oauth/token/request
rgupta@rgupta-mac .ssh % oc login --token=sha256~q8J2fwLIdNFbZ-C5iVv50XzXD4bOcztNABs-Y_uW8Cw --server=https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443" as "opentlc-mgr" using the token provided.

You have access to 70 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac .ssh % oc project user1-cache2
Now using project "user1-cache2" on server "https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443".
rgupta@rgupta-mac .ssh % echo "https://$(oc get services | grep example-lon-external | awk '{ print $4 }'):11222"
https://:11222
rgupta@rgupta-mac .ssh % echo "$(oc get secret example-lon-generated-secret -o jsonpath="{.data.identities\.yaml}" | base64 --decode | grep password | awk '{ print $2 }' )"
zlROywKSPBorCSOE
rgupta@rgupta-mac .ssh % oc get services | grep example-lon-external
rgupta@rgupta-mac .ssh % oc get services                            
NAME                                             TYPE        CLUSTER-IP       EXTERNAL-IP   PORT(S)     AGE
example-lon                                      ClusterIP   172.30.0.113     <none>        11222/TCP   10m
example-lon-admin                                ClusterIP   None             <none>        11223/TCP   10m
example-lon-ping                                 ClusterIP   None             <none>        8888/TCP    10m
example-lon-site                                 ClusterIP   172.30.217.197   <none>        7900/TCP    10m
infinispan-operator-controller-manager-service   ClusterIP   172.30.203.174   <none>        443/TCP     41h
rgupta@rgupta-mac .ssh % oc get services | grep example-lon-external
example-lon-external                             LoadBalancer   172.30.215.40    a3612ca1afc1246f196158a888dd5260-809766529.us-east-2.elb.amazonaws.com   11222:30876/TCP   16s
rgupta@rgupta-mac .ssh % oc project
Using project "user1-cache2" on server "https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443".
rgupta@rgupta-mac .ssh % oc project user1-cache
Now using project "user1-cache" on server "https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443".
rgupta@rgupta-mac .ssh % echo "https://$(oc get services | grep example-nyc-external | awk '{ print $4 }'):11222"
https://a5e476dfa21924505b778a0fe7179cf3-709516714.us-east-2.elb.amazonaws.com:11222
rgupta@rgupta-mac .ssh % echo "$(oc get secret example-nyc-generated-secret -o jsonpath="{.data.identities\.yaml}" | base64 --decode | grep password | awk '{ print $2 }' )"
UlYncZiCubJEbSUP
rgupta@rgupta-mac .ssh % oc project user1-cache2
Now using project "user1-cache2" on server "https://api.cluster-hk6cl.hk6cl.sandbox338.opentlc.com:6443".
rgupta@rgupta-mac .ssh %  echo "https://$(oc get services | grep example-lon-external | awk '{ print $4 }'):11222"
https://a3612ca1afc1246f196158a888dd5260-809766529.us-east-2.elb.amazonaws.com:11222
rgupta@rgupta-mac .ssh % oc get nodes -o wide
NAME                                         STATUS   ROLES    AGE   VERSION           INTERNAL-IP    EXTERNAL-IP   OS-IMAGE                                                        KERNEL-VERSION                 CONTAINER-RUNTIME
ip-10-0-132-245.us-east-2.compute.internal   Ready    master   42h   v1.23.5+8471591   10.0.132.245   <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
ip-10-0-176-105.us-east-2.compute.internal   Ready    worker   42h   v1.23.5+8471591   10.0.176.105   <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
ip-10-0-178-83.us-east-2.compute.internal    Ready    master   42h   v1.23.5+8471591   10.0.178.83    <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
ip-10-0-190-8.us-east-2.compute.internal     Ready    master   42h   v1.23.5+8471591   10.0.190.8     <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
ip-10-0-218-82.us-east-2.compute.internal    Ready    worker   42h   v1.23.5+8471591   10.0.218.82    <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
ip-10-0-247-205.us-east-2.compute.internal   Ready    worker   42h   v1.23.5+8471591   10.0.247.205   <none>        Red Hat Enterprise Linux CoreOS 410.84.202210040010-0 (Ootpa)   4.18.0-305.62.1.el8_4.x86_64   cri-o://1.23.3-17.rhaos4.10.git016b1ca.el8
rgupta@rgupta-mac .ssh % clear

rgupta@rgupta-mac .ssh % oc login https://api.cluster-8hmgc.8hmgc.sandbox1544.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-8hmgc.8hmgc.sandbox1544.opentlc.com/oauth/token/request
rgupta@rgupta-mac .ssh % oc login --token=sha256~LEZca9S3j5f1W-_T4gcDaizjKW5ukOaqWoKCh8AMTTQ --server=https://api.cluster-8hmgc.8hmgc.sandbox1544.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-8hmgc.8hmgc.sandbox1544.opentlc.com:6443" as "user1" using the token provided.

You have access to the following projects and can switch between them with 'oc project <projectname>':

    user1-cache
  * user1-cache2

Using project "user1-cache2".
rgupta@rgupta-mac .ssh % oc get secret datagrid-service-generated-secret -o jsonpath="{.data.identities\.yaml}" | base64 --decode
Error from server (NotFound): secrets "datagrid-service-generated-secret" not found
rgupta@rgupta-mac .ssh % echo "$(oc get secret example-lon-generated-secret -o jsonpath="{.data.identities\.yaml}" | base64 --decode | grep password | awk '{ print $2 }' )"
Error from server (NotFound): secrets "example-lon-generated-secret" not found

rgupta@rgupta-mac .ssh % 































  [Restored Jul 29, 2023 at 7:36:53 AM]
Last login: Sat Jul 29 07:36:49 on console
rgupta@rgupta-mac .ssh % traceroute
Version 1.4a12+Darwin
Usage: traceroute [-adDeFInrSvx] [-A as_server] [-f first_ttl] [-g gateway] [-i iface]
	[-M first_ttl] [-m max_ttl] [-p port] [-P proto] [-q nqueries] [-s src_addr]
	[-t tos] [-w waittime] [-z pausemsecs] host [packetlen]
rgupta@rgupta-mac .ssh % pwd
/Users/rgupta/.ssh
rgupta@rgupta-mac .ssh % ls
book-import	config		id_rsa		id_rsa.pub	known_hosts
rgupta@rgupta-mac .ssh % cd ~
rgupta@rgupta-mac ~ % ls
Applications	Desktop		Documents	Downloads	Library		Movies		Music		Pictures	Public		VirtualBox VMs
rgupta@rgupta-mac ~ % cd Documents 
rgupta@rgupta-mac Documents % ls
512 society								expenses								openshift
L-What's%20New%20in%20OpenShift%20Container%20Platform%204.7.pptx_0.odp	keycloak								personal
WebEx									learning								principal
accounts								mcclane
rgupta@rgupta-mac Documents % cd accounts 
rgupta@rgupta-mac accounts % ls
Maimonides			bankofhawaii			crown				discount			iodine				myriad				techm
Video_20230707_191207_174.mp4	cd.png				d.svg				doxy-2023.3gp			laird				svgtopng (1)			thirdfederal
alegro				cerberus			demo.png			evolveip			max				svgtopng (1).zip		zions bank
an.jpeg				cig				demo.svg			ibm-2				mclane				svgtopng.zip
rgupta@rgupta-mac accounts % mkdir BKansas
rgupta@rgupta-mac accounts % cd BKansas 
rgupta@rgupta-mac BKansas % ls
rgupta@rgupta-mac BKansas % git clone https://github.com/siamaksade/openshift-cicd-demo.git
Cloning into 'openshift-cicd-demo'...
remote: Enumerating objects: 321, done.
remote: Counting objects: 100% (138/138), done.
remote: Compressing objects: 100% (40/40), done.
remote: Total 321 (delta 109), reused 107 (delta 98), pack-reused 183
Receiving objects: 100% (321/321), 1.44 MiB | 5.44 MiB/s, done.
Resolving deltas: 100% (180/180), done.
rgupta@rgupta-mac BKansas % ls
openshift-cicd-demo
rgupta@rgupta-mac BKansas % cd *
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % oc login https://api.cluster-f9q98.sandbox357.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

You must obtain an API token by visiting https://oauth-openshift.apps.cluster-f9q98.sandbox357.opentlc.com/oauth/token/request
rgupta@rgupta-mac openshift-cicd-demo % oc login --token=sha256~LVFj-C7pfrTk5SAP0BaahUnYHVtP2sOHivAAxxiXLFM --server=https://api.cluster-f9q98.sandbox357.opentlc.com:6443
The server uses a certificate signed by an unknown authority.
You can bypass the certificate check, but any data you send to the server could be intercepted by others.
Use insecure connections? (y/n): y

Logged into "https://api.cluster-f9q98.sandbox357.opentlc.com:6443" as "admin" using the token provided.

You have access to 81 projects, the list has been suppressed. You can list all projects with 'oc projects'

Using project "default".
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % oc new-project demo
Now using project "demo" on server "https://api.cluster-f9q98.sandbox357.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh 

  Usage:
      demo [command] [options]

  Example:
      demo install --project-prefix mydemo

  COMMANDS:
      install                        Sets up the demo and creates namespaces
      uninstall                      Deletes the demo
      start                          Starts the deploy DEV pipeline
      help                           Help about this command

  OPTIONS:
      -p|--project-prefix [string]   Prefix to be added to demo project names e.g. PREFIX-dev
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
Now using project "demo-cicd" on server "https://api.cluster-f9q98.sandbox357.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-dev" on server "https://api.cluster-f9q98.sandbox357.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname

Now using project "demo-stage" on server "https://api.cluster-f9q98.sandbox357.opentlc.com:6443".

You can add applications to this project with the 'new-app' command. For example, try:

    oc new-app rails-postgresql-example

to build a new example application in Ruby. Or use kubectl to deploy a simple Kubernetes application:

    kubectl create deployment hello-node --image=k8s.gcr.io/serve_hostname


# INFO: Configure service account permissions for pipeline
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
Warning: ServiceAccount 'pipeline' not found
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea created
service/gitea-postgresql created
deployment.apps/gitea-postgresql created
service/gitea created
route.route.openshift.io/gitea created
deployment.apps/gitea created
persistentvolumeclaim/gitea-repositories created
persistentvolumeclaim/gitea-postgres-data created
deployment.apps/nexus created
service/nexus created
route.route.openshift.io/nexus created
persistentvolumeclaim/nexus-pv created
deployment.apps/sonarqube created
route.route.openshift.io/sonarqube created
service/sonarqube created

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): namespaces "openshift-pipelines" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   2m30s
NAME       STATUS   AGE
demo-dev   Active   2m29s
NAME         STATUS   AGE
demo-stage   Active   2m27s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): namespaces "openshift-pipelines" not found
rgupta@rgupta-mac openshift-cicd-demo % oc new-project openshift-pipelines
Error from server (Forbidden): project.project.openshift.io "openshift-pipelines" is forbidden: cannot request a project starting with "openshift-"
rgupta@rgupta-mac openshift-cicd-demo % oc new-project openshift-pipelines
Error from server (Forbidden): project.project.openshift.io "openshift-pipelines" is forbidden: cannot request a project starting with "openshift-"
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install                 

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   2m56s
NAME       STATUS   AGE
demo-dev   Active   2m54s
NAME         STATUS   AGE
demo-stage   Active   2m53s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   4m24s
NAME       STATUS   AGE
demo-dev   Active   4m22s
NAME         STATUS   AGE
demo-stage   Active   4m20s

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
Error from server (NotFound): routes.route.openshift.io "pipelines-as-code-controller" not found
rgupta@rgupta-mac openshift-cicd-demo % ./demo.sh install

# INFO: Creating namespaces demo-cicd, demo-dev, demo-stage
NAME        STATUS   AGE
demo-cicd   Active   17m
NAME       STATUS   AGE
demo-dev   Active   17m
NAME         STATUS   AGE
demo-stage   Active   17m

# INFO: Configure service account permissions for pipeline
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/edit added: "system:serviceaccount:demo-cicd:pipeline"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-dev:default"
clusterrole.rbac.authorization.k8s.io/system:image-puller added: "system:serviceaccount:demo-stage:default"

# INFO: Deploying CI/CD infra to demo-cicd namespace
serviceaccount/gitea unchanged
service/gitea-postgresql unchanged
deployment.apps/gitea-postgresql configured
service/gitea unchanged
route.route.openshift.io/gitea unchanged
deployment.apps/gitea unchanged
persistentvolumeclaim/gitea-repositories unchanged
persistentvolumeclaim/gitea-postgres-data unchanged
deployment.apps/nexus configured
service/nexus unchanged
route.route.openshift.io/nexus unchanged
persistentvolumeclaim/nexus-pv unchanged
deployment.apps/sonarqube unchanged
route.route.openshift.io/sonarqube unchanged
service/sonarqube unchanged

# INFO: Initiatlizing git repository in Gitea and configuring webhooks
configmap/gitea-config created
Waiting for deployment "gitea" rollout to finish: 0 of 1 updated replicas are available...
deployment "gitea" successfully rolled out
taskrun.tekton.dev/init-gitea-l5qxn created
.

Waiting for source code to be imported to Gitea...
.

.

.

.

.

.

.

.

.

.

.

.

.


# INFO: Updated pipelinerun values for the demo environment
/var/folders/tk/cyhkspls623bs4nvt5dzkkp40000gn/T/tmp.nvl510ho ~/Documents/accounts/BKansas/openshift-cicd-demo
Cloning into 'spring-petclinic'...
remote: Enumerating objects: 9302, done.
remote: Counting objects: 100% (9302/9302), done.
remote: Compressing objects: 100% (4441/4441), done.
remote: Total 9302 (delta 3573), reused 9302 (delta 3573), pack-reused 0
Receiving objects: 100% (9302/9302), 6.95 MiB | 5.21 MiB/s, done.
Resolving deltas: 100% (3573/3573), done.
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: https://github.com/siamaksade/spring-petclinic-config
          - name: GIT_USERNAME
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
--
          - name: GIT_REPOSITORY
            value: http://gitea-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com/gitea/spring-petclinic-config
          - name: GIT_USERNAME
On branch cicd-demo
Your branch is up to date with 'origin/cicd-demo'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   .tekton/build.yaml

no changes added to commit (use "git add" and/or "git commit -a")
[cicd-demo b3e171a] Updated manifests git url
 1 file changed, 2 insertions(+), 2 deletions(-)
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 455 bytes | 455.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: . Processing 1 references
remote: Processed 1 references in total
To http://gitea-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com/gitea/spring-petclinic
   aacbbb4..b3e171a  cicd-demo -> cicd-demo
~/Documents/accounts/BKansas/openshift-cicd-demo

# INFO: Configuring pipelines-as-code
repository.pipelinesascode.tekton.dev/spring-petclinic created
secret/gitea created
.


# INFO: Configure Argo CD
appproject.argoproj.io/spring-petclinic created
application.argoproj.io/dev-spring-petclinic created
application.argoproj.io/stage-spring-petclinic created
argocd.argoproj.io/argocd created

# INFO: Wait for Argo CD route...
.


# INFO: Grants permissions to ArgoCD instances to manage resources in target namespaces
namespace/demo-dev labeled
namespace/demo-stage labeled
Now using project "demo-cicd" on server "https://api.cluster-f9q98.sandbox357.opentlc.com:6443".

############################################################################
############################################################################

  Demo is installed! Give it a few minutes to finish deployments and then:

  1) Go to spring-petclinic Git repository in Gitea:
     http://gitea-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com/gitea/spring-petclinic.git

  2) Log into Gitea with username/password: gitea/openshift

  3) Edit a file in the repository and commit to trigger the pipeline (alternatively, create a pull-request)

  4) Check the pipeline run logs in Dev Console or Tekton CLI:

    $ opc pac logs -n demo-cicd


  You can find further details at:

  Gitea Git Server: http://gitea-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com/explore/repos
  SonarQube: https://sonarqube-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com
  Sonatype Nexus: http://nexus-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com
  Argo CD:  http://argocd-server-demo-cicd.apps.cluster-f9q98.sandbox357.opentlc.com  [login with OpenShift credentials]

############################################################################
############################################################################
rgupta@rgupta-mac openshift-cicd-demo % oc get co
NAME                                       VERSION   AVAILABLE   PROGRESSING   DEGRADED   SINCE   MESSAGE
authentication                             4.13.6    True        False         False      3h      
baremetal                                  4.13.6    True        False         False      3h18m   
cloud-controller-manager                   4.13.6    True        False         False      3h21m   
cloud-credential                           4.13.6    True        False         False      3h21m   
cluster-autoscaler                         4.13.6    True        False         False      3h18m   
config-operator                            4.13.6    True        False         False      3h19m   
console                                    4.13.6    True        False         False      3h1m    
control-plane-machine-set                  4.13.6    True        False         False      3h15m   
csi-snapshot-controller                    4.13.6    True        False         False      3h18m   
dns                                        4.13.6    True        False         False      3h18m   
etcd                                       4.13.6    True        False         False      3h17m   
image-registry                             4.13.6    True        False         False      3h13m   
ingress                                    4.13.6    True        False         False      3h13m   
insights                                   4.13.6    True        False         False      3h12m   
kube-apiserver                             4.13.6    True        False         False      3h15m   
kube-controller-manager                    4.13.6    True        False         False      3h15m   
kube-scheduler                             4.13.6    True        False         False      3h15m   
kube-storage-version-migrator              4.13.6    True        False         False      3h19m   
machine-api                                4.13.6    True        False         False      3h15m   
machine-approver                           4.13.6    True        False         False      3h18m   
machine-config                             4.13.6    True        False         False      3h16m   
marketplace                                4.13.6    True        False         False      3h19m   
monitoring                                 4.13.6    True        False         False      3h12m   
network                                    4.13.6    True        False         False      3h21m   
node-tuning                                4.13.6    True        False         False      3h18m   
openshift-apiserver                        4.13.6    True        False         False      3h13m   
openshift-controller-manager               4.13.6    True        False         False      3h14m   
openshift-samples                          4.13.6    True        False         False      3h12m   
operator-lifecycle-manager                 4.13.6    True        False         False      3h18m   
operator-lifecycle-manager-catalog         4.13.6    True        False         False      3h18m   
operator-lifecycle-manager-packageserver   4.13.6    True        False         False      3h13m   
service-ca                                 4.13.6    True        False         False      3h19m   
storage                                    4.13.6    True        False         False      3h18m   
rgupta@rgupta-mac openshift-cicd-demo % 
rgupta@rgupta-mac openshift-cicd-demo % 
rgupta@rgupta-mac openshift-cicd-demo % ls
LICENSE		README.md	argo		config		demo.sh		docs		infra		triggers
rgupta@rgupta-mac openshift-cicd-demo % cd ..
rgupta@rgupta-mac BKansas % cd ..
rgupta@rgupta-mac accounts % ls
BKansas				an.jpeg				cig				demo.svg			ibm-2				mclane				svgtopng.zip
Maimonides			bankofhawaii			crown				discount			iodine				myriad				techm
Video_20230707_191207_174.mp4	cd.png				d.svg				doxy-2023.3gp			laird				svgtopng (1)			thirdfederal
alegro				cerberus			demo.png			evolveip			max				svgtopng (1).zip		zions bank
rgupta@rgupta-mac accounts % pwd
/Users/rgupta/Documents/accounts
rgupta@rgupta-mac accounts % pwd
/Users/rgupta/Documents/accounts
rgupta@rgupta-mac accounts % cd BKansas 
rgupta@rgupta-mac BKansas % git clone https://github.com/tolarewaju3/codelikethewind.git
Cloning into 'codelikethewind'...
remote: Enumerating objects: 772, done.
remote: Counting objects: 100% (101/101), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 772 (delta 89), reused 60 (delta 60), pack-reused 671
Receiving objects: 100% (772/772), 295.48 KiB | 2.17 MiB/s, done.
Resolving deltas: 100% (220/220), done.
rgupta@rgupta-mac BKansas % ls
codelikethewind		openshift-cicd-demo
rgupta@rgupta-mac BKansas % cd codelikethewind 
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % cd ..
rgupta@rgupta-mac BKansas % git checkout openshift-jenkins-pipeline 
fatal: not a git repository (or any of the parent directories): .git
rgupta@rgupta-mac BKansas % pwd
/Users/rgupta/Documents/accounts/BKansas
rgupta@rgupta-mac BKansas % ls
codelikethewind		openshift-cicd-demo
rgupta@rgupta-mac BKansas % cd codelikethewind 
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline 
branch 'openshift-jenkins-pipeline' set up to track 'origin/openshift-jenkins-pipeline'.
Switched to a new branch 'openshift-jenkins-pipeline'
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 
rgupta@rgupta-mac codelikethewind % pwd
/Users/rgupta/Documents/accounts/BKansas/codelikethewind
rgupta@rgupta-mac codelikethewind % cd ..
rgupta@rgupta-mac BKansas % ls
codelikethewind		openshift-cicd-demo
rgupta@rgupta-mac BKansas % mkdir ravi
rgupta@rgupta-mac BKansas % cd ravi
rgupta@rgupta-mac ravi % git clone https://github.com/rgupta1234/codelikethewind.git
Cloning into 'codelikethewind'...
remote: Enumerating objects: 655, done.
remote: Counting objects: 100% (57/57), done.
remote: Compressing objects: 100% (15/15), done.
remote: Total 655 (delta 51), reused 42 (delta 42), pack-reused 598
Receiving objects: 100% (655/655), 279.07 KiB | 2.21 MiB/s, done.
Resolving deltas: 100% (152/152), done.
rgupta@rgupta-mac ravi % ls
codelikethewind
rgupta@rgupta-mac ravi % cd *
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline
error: pathspec 'openshift-jenkins-pipeline' did not match any file(s) known to git
rgupta@rgupta-mac codelikethewind % pw
zsh: command not found: pw
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % cd ..
rgupta@rgupta-mac ravi % git checkout openshift-jenkins-pipeline
fatal: not a git repository (or any of the parent directories): .git
rgupta@rgupta-mac ravi % =ls
codelikethewind
rgupta@rgupta-mac ravi % cd *
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline
error: pathspec 'openshift-jenkins-pipeline' did not match any file(s) known to git
rgupta@rgupta-mac codelikethewind % git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--config-env=<name>=<envvar>] <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
rgupta@rgupta-mac codelikethewind % git checkout
Your branch is up to date with 'origin/master'.
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline
error: pathspec 'openshift-jenkins-pipeline' did not match any file(s) known to git
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % cd ..
rgupta@rgupta-mac ravi % ls
codelikethewind
rgupta@rgupta-mac ravi % rm -rf *
zsh: sure you want to delete the only file in /Users/rgupta/Documents/accounts/BKansas/ravi [yn]? y
rgupta@rgupta-mac ravi % ls
rgupta@rgupta-mac ravi % pwd
/Users/rgupta/Documents/accounts/BKansas/ravi
rgupta@rgupta-mac ravi % git clone https://github.com/tolarewaju3/codelikethewind.git
Cloning into 'codelikethewind'...
remote: Enumerating objects: 772, done.
remote: Counting objects: 100% (101/101), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 772 (delta 89), reused 60 (delta 60), pack-reused 671
Receiving objects: 100% (772/772), 295.48 KiB | 1.51 MiB/s, done.
Resolving deltas: 100% (220/220), done.
rgupta@rgupta-mac ravi % ls
codelikethewind
rgupta@rgupta-mac ravi % cd *
rgupta@rgupta-mac codelikethewind % ls
LICENSE					ejb-server-side				quarkus-dev-joy				simple-maven-project			simple-rest-service
README.md				ejb-standalone-client-eap6		simple-data-model			simple-process				simple-servlet
ansible-jboss-cluster			ejb-standalone-client-eap7		simple-ejb-project			simple-process-workitemhandler		simple-servlet-codeready
data-operation				embedded-process-workitemhandler	simple-embedded-process			simple-remoteejb-project		starter-projects
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline                     
branch 'openshift-jenkins-pipeline' set up to track 'origin/openshift-jenkins-pipeline'.
Switched to a new branch 'openshift-jenkins-pipeline'
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % cd ..
rgupta@rgupta-mac ravi % ls
codelikethewind
rgupta@rgupta-mac ravi % rm -rf *
zsh: sure you want to delete the only file in /Users/rgupta/Documents/accounts/BKansas/ravi [yn]? y
rgupta@rgupta-mac ravi % 
rgupta@rgupta-mac ravi % ls
rgupta@rgupta-mac ravi % git clone https://github.com/rgupta1234/codelikethewind.git
Cloning into 'codelikethewind'...
remote: Enumerating objects: 772, done.
remote: Counting objects: 100% (101/101), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 772 (delta 89), reused 60 (delta 60), pack-reused 671
Receiving objects: 100% (772/772), 295.48 KiB | 2.40 MiB/s, done.
Resolving deltas: 100% (220/220), done.
rgupta@rgupta-mac ravi % git checkout openshift-jenkins-pipeline                    
fatal: not a git repository (or any of the parent directories): .git
rgupta@rgupta-mac ravi % ls
codelikethewind
rgupta@rgupta-mac ravi % cd *
rgupta@rgupta-mac codelikethewind % git checkout openshift-jenkins-pipeline                    
branch 'openshift-jenkins-pipeline' set up to track 'origin/openshift-jenkins-pipeline'.
Switched to a new branch 'openshift-jenkins-pipeline'
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % cp ../codelikethewind/Jenkinsfile .
cp: ./Jenkinsfile and ../codelikethewind/Jenkinsfile are identical (not copied).
rgupta@rgupta-mac codelikethewind % cp ../../codelikethewind/Jenkinsfile .
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 
rgupta@rgupta-mac codelikethewind % git commit -a -m "dfd"
[openshift-jenkins-pipeline 27c95ca] dfd
 1 file changed, 27 insertions(+), 3 deletions(-)
rgupta@rgupta-mac codelikethewind % git push
Username for 'https://github.com': rgupta1234
Password for 'https://rgupta1234@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/rgupta1234/codelikethewind.git/'
rgupta@rgupta-mac codelikethewind % git push
Username for 'https://github.com': rgupta1234
Password for 'https://rgupta1234@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/rgupta1234/codelikethewind.git/'
rgupta@rgupta-mac codelikethewind % git push
Username for 'https://github.com': rgupta1234
Password for 'https://rgupta1234@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/rgupta1234/codelikethewind.git/'
rgupta@rgupta-mac codelikethewind % ls
Jenkinsfile	LICENSE		README.md	pom.xml		src
rgupta@rgupta-mac codelikethewind % vi Jenkinsfile 

#! /usr/bin/env groovy

pipeline {

  agent {
    label 'maven'
  }

  stages {
    stage('Build') {
      steps {
        echo 'Building..'
         sh 'mvn clean package'
        // Add steps here
      }
    }
    stage('Create Container Image') {
      steps {
        echo 'Create Container Image..'

        script {

           openshift.withCluster() {
  openshift.withProject("jenkins-1") {

    def buildConfigExists = openshift.selector("bc", "codelikethewind").exists()

    if(!buildConfigExists){
      openshift.newBuild("--name=codelikethewind", "--docker-image=registry.redhat.io/jboss-eap-7/eap74-openjdk8-openshift-rhel7", "--binary")
    }

    openshift.selector("bc", "codelikethewind").startBuild("--from-file=target/simple-servlet-0.0.1-SNAPSHOT.war", "--follow") } }

        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
        script {

          // Add steps here
           openshift.withCluster() {
  openshift.withProject("jenkins-1") {
    def deployment = openshift.selector("dc", "codelikethewind")

    if(!deployment.exists()){
      openshift.newApp('codelikethewind', "--as-deployment-config").narrow('svc').expose()
    }

    timeout(5) {
      openshift.selector("dc", "codelikethewind").related('pods').untilEach(1) {
        return (it.object().status.phase == "Running")
      }
    }
"Jenkinsfile" 63L, 1452B
