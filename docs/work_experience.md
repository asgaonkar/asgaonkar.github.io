---
layout: default_card
title: Work Experience
nav_order: 5
permalink: /work_experience/
description: "Atit Gaonkar - Working as Information Security (Intern) and Data Engineer (Intern) honed my Cyber-Security and Data Science skills."
---

<style>

.horizontal-rule{
    border-top: 1px solid #DDD;
}

</style>

# Work Experience
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---



## Data Engineer (Intern)
{: .d-inline-block .mr-2}

2019
{: .label .label-green}

[Tulip Diagnostics](http://www.tulipgroup.com/){: .target-blank} (A [Perkin Elmer](https://www.perkinelmer.com/){: .target-blank} Company), Vasco, India
{: .mb-0}
Jan 2019 - Apr 2019
{: .mb-2}

<div class="horizontal-rule mb-4"></div>

<!-- [![Tulip Diagnostics][Tulip-Diagnostics-img]{: .img-responsive .logo .d-inline-block .logo-link height="10%" width="10%"}][Tulip-Diagnostics-link]

[Tulip-Diagnostics-img]:  ../../assets/images/tulip.jpg
[Tulip-Diagnostics-link]:  http://www.tulipgroup.com/ "Redirect to - Tulip Diagnostics"  -->

Analyzed internal processes, business operation and sales structure to create [Info-graphic Dashboards](https://en.wikipedia.org/wiki/Dashboard_(business)){: .target-blank} using Microsoft’s business intelligence tools, [SSAS](https://docs.microsoft.com/en-us/analysis-services/analysis-services-overview?view=asallproducts-allversions){: .target-blank}, [SSIS](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services?view=sql-server-ver15){: .target-blank} and [SSRS](https://docs.microsoft.com/en-us/sql/reporting-services/create-deploy-and-manage-mobile-and-paginated-reports?view=sql-server-ver15){: .tagret-blank}. Used Visualization Tools such as [Power BI](https://powerbi.microsoft.com/en-us/){: .target-blank} and [TIBCO Spotfire](https://www.tibco.com/products/tibco-spotfire){: .target-blank} to enhance the process of decision making.

Automated the process of interpreting dashboards and forecasting projected revenue using VBA and SQL. Redesigned reporting system resulting in increased efficiency of 81.25%, hence reducing the time spent on month-end analysis. 

## Information Security (Intern)
{: .d-inline-block .mr-2 }

2019
{: .label .label-green}

[Tulip Diagnostics](http://www.tulipgroup.com/){: .target-blank} (A [Perkin Elmer](https://www.perkinelmer.com/){: .target-blank} Company), Vasco, India
{: .mb-0}
Jan 2019 - Apr 2019
{: .mb-2}

<div class="horizontal-rule mb-4"></div>

<!-- [![Tulip Diagnostics][Tulip-Diagnostics-img]{: .img-responsive .logo .d-inline-block .logo-link height="10%" width="10%"}][Tulip-Diagnostics-link]

[Tulip-Diagnostics-img]:  ../../assets/images/tulip.jpg
[Tulip-Diagnostics-link]:  http://www.tulipgroup.com/ "Redirect to - Tulip Diagnostics"  -->

Worked Closely with Database Administrators and Network Managers to establish new security guidelines and practices.

Executed regular network evaluation and vulnerability scans. Significantly improved security processes. 

<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
  $(window).on('load', function() {
        AOS.refresh();
        var $animation_elements = $('.bootstrap-iso');
        var $window = $(window);
        var window_height = $window.height();
        var window_top_position = $window.scrollTop();
        var window_bottom_position = (window_top_position + window_height);
        $('.target-blank').attr('target','blank');
        $('pre').addClass("mb-0");
        $('p > a.no-mb').parent().addClass("mb-0");
        $('a > img').parent().addClass("image-link");
        $('img.logo-link').parent().attr('target','blank');
        $('.main-content-wrap').on('scroll', function() {
            console.log("triggered");
            $.each($animation_elements, function() {
                var $element = $(this);
                var element_height = $element.outerHeight();
                var element_top_position = $element.offset().top;
                var element_bottom_position = (element_top_position + element_height);
                if ((element_bottom_position >= window_top_position) && (element_top_position <= window_bottom_position)) {
                    $element.addClass('aos-animate');
                } else {
                    $element.removeClass('aos-animate');
                }
            });
        });
        $('.main-content-wrap')[0].scrollTop += 1;
        $('.main-content-wrap')[0].scrollTop -= 1;
  });
</script>