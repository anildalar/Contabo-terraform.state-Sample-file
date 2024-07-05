# Contabo-terraform.state-Sample-file
Contabo terraform.state Sample file

{
  "version": 4,
  "terraform_version": "1.9.1",
  "serial": 1,
  "lineage": "03342edb-387c-fced-96ff-3e09cc2c8133",
  "outputs": {},
  "resources": [
    {
      "mode": "managed",
      "type": "contabo_instance",
      "name": "pbxvps",
      "provider": "provider[\"registry.terraform.io/contabo/contabo\"]",
      "instances": [
        {
          "schema_version": 0,
          "attributes": {
            "add_ons": [],
            "additional_ips": [],
            "cancel_date": "",
            "cpu_cores": 4,
            "created_date": "Friday, 05-Jul-24 08:02:36 UTC",
            "disk_mb": 102400,
            "display_name": "",
            "error_message": "",
            "existing_instance_id": null,
            "id": "201987085",
            "image_id": "35f3129d-5b02-45ff-9137-e8a12d2832ec",
            "ip_config": [
              {
                "v4": [
                  {
                    "gateway": "38.242.224.1",
                    "ip": "38.242.226.196",
                    "netmask_cidr": 19
                  }
                ],
                "v6": [
                  {
                    "gateway": "fe80::1",
                    "ip": "2a02:c206:2198:7085:0000:0000:0000:0001",
                    "netmask_cidr": 64
                  }
                ]
              }
            ],
            "last_updated": null,
            "license": null,
            "mac_address": "00:50:56:53:53:c2",
            "name": "vmi1987085",
            "os_type": "Linux",
            "period": 1,
            "product_id": "V46",
            "product_type": "nvme",
            "ram_mb": 6144,
            "region": "EU",
            "root_password": null,
            "ssh_keys": [],
            "status": "running",
            "user_data": null,
            "v_host_id": 14366
          },
          "sensitive_attributes": [],
          "private": "bnVsbA=="
        }
      ]
    }
  ],
  "check_results": null
}

