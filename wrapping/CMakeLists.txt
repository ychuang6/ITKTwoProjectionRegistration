itk_wrap_module(TwoProjectionRegistration)

set(WRAPPER_SUBMODULE_ORDER
   itkNormalizedCorrelationTwoImageToOneImageMetric
   itkSiddonJacobsRayCastInterpolateImageFunction
   itkTwoImageToOneImageMetric
   itkTwoProjectionImageRegistrationMethod)

itk_auto_load_submodules()
itk_end_wrap_module()

