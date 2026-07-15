function ($scope) {

    $scope.slaDetails = {
        incident: "INC0010001",
        priority: "High",
        status: "In Progress",
        sla: "2 Hours",
        remaining: "35 Minutes"
    };

    $scope.submitJustification = function () {
        alert("SLA Justification Submitted Successfully.");
    };

}
