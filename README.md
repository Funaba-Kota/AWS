参考：https://dev.classmethod.jp/articles/put-together-about-the-relationship-between-cfn-and-management-console-items/



実行ロール に当たる部分は、 Credentials にIAM RoleのARN文字列（e.g. !GetAtt ApiGatewayRole.Arn）で指定します。

