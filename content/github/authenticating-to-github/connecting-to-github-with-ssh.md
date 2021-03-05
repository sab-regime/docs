import 'package:flutter/material.dart';

class IconExample extends StatelessWidget {
  const IconExample({Key key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return Center(
      child: Icon(
        Icons.image,
        size: 64.0,
        color: Theme.of(context).primaryColor,
      ),
    );
  }
}
---
title: Connecting to GitHub with SSH
intro: 'You can connect to {% data variables.product.product_name %} using SSH.'
redirect_from:
  - /key-setup-redirect/
  - /linux-key-setup/
  - /mac-key-setup/
  - /msysgit-key-setup/
  - /articles/ssh-key-setup/
  - /articles/generating-ssh-keys/
  - /articles/generating-an-ssh-key/
  - /articles/connecting-to-github-with-ssh
mapTopic: true
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
---

