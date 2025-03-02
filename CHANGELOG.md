# Changelog

All notable changes to this project will be documented in this file.

## [1.4.1](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.4.0...v1.4.1) (2024-09-05)


### Bug Fixes

* Change `association_defaults` type from `map(string)` to `any` to support tags ([#15](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/15)) ([85f2516](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/85f25165c7a115738d053ff93fa24b3d3701fb4b))

## [1.4.0](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.3.0...v1.4.0) (2024-08-07)


### Features

* Add cloudwatch logs policy to vpc-cni for networkpolicy logging ([#13](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/13)) ([a5da73e](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/a5da73e26a8d4ca46f76ea5e4e0c57479a451837))

## [1.3.0](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.2.1...v1.3.0) (2024-07-21)


### Features

* Add support for specifying assume role conditions ([#12](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/12)) ([5249afc](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/5249afcf2c5c8f7347c48d4bc8caab193dcf5e20))

## [1.2.1](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.2.0...v1.2.1) (2024-05-30)


### Bug Fixes

* TargetGroup Binding only policy requires policies for SecurityGroup ([#10](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/10)) ([ba34af4](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/ba34af404af6dd45a387dc8689e07183667afc58))

## [1.2.0](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.1.0...v1.2.0) (2024-04-02)


### Features

* Add fast snapshot restore policy to ebs csi role ([#5](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/5)) ([10f90d6](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/10f90d6d92e23b66520a92d9f80870d008825fdd))

## [1.1.0](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/compare/v1.0.0...v1.1.0) (2024-03-21)


### Features

* Add support for creating pod identity associations ([#4](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/issues/4)) ([98c5bdf](https://github.com/terraform-aws-modules/terraform-aws-eks-pod-identity/commit/98c5bdf103094e907315c980981841efae26ae2b))
