.. _implementedservice_eks:

.. |start-h3| raw:: html

    <h3>

.. |end-h3| raw:: html

    </h3>

===
eks
===

|start-h3| Example usage |end-h3|

.. sourcecode:: python

            @mock_eks
            def test_eks_behaviour:
                boto3.client("eks")
                ...



|start-h3| Implemented features for this service |end-h3|

- [ ] associate_encryption_config
- [ ] associate_identity_provider_config
- [ ] create_addon
- [X] create_cluster
- [X] create_fargate_profile
- [X] create_nodegroup
- [ ] delete_addon
- [X] delete_cluster
- [X] delete_fargate_profile
- [X] delete_nodegroup
- [ ] deregister_cluster
- [ ] describe_addon
- [ ] describe_addon_versions
- [X] describe_cluster
- [X] describe_fargate_profile
- [ ] describe_identity_provider_config
- [X] describe_nodegroup
- [ ] describe_update
- [ ] disassociate_identity_provider_config
- [ ] list_addons
- [X] list_clusters
- [X] list_fargate_profiles
- [ ] list_identity_provider_configs
- [X] list_nodegroups
- [ ] list_tags_for_resource
- [ ] list_updates
- [ ] register_cluster
- [ ] tag_resource
- [ ] untag_resource
- [ ] update_addon
- [ ] update_cluster_config
- [ ] update_cluster_version
- [ ] update_nodegroup_config
- [ ] update_nodegroup_version

