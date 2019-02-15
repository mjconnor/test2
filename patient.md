# Patient

/\*

* Copyright 2009-2017 C3 IoT, Inc. All Rights Reserved.
* This material, including without limitation any software, is the confidential trade secret
* and proprietary information of C3 IoT and its licensors. Reproduction, use and/or distribution
* of this material in any form is strictly prohibited except as set forth in a written
* license agreement with C3 IoT and/or its authorized distributors.
* This product may be covered by one or more U.S. patents or pending patent applications.

  ~\*/

/_\*_ / entity type Patient mixes MetricEvaluatable schema name "PT" {

/\*\*

* This patients historical measurements. \*/ patientMeasurements: [PatientMeasurementSeries](https://github.com/mjconnor/test2/tree/bc1aa7789212117c0e9bfea8efda94b16eb49338/patient/README.md)

  /_\*_ / recid: string

}

