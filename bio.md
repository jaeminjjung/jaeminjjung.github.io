<html lang="en-uk" data-bs-theme="light"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<main class="col-md-7">
                    <p>David J. Malan is Gordon McKay Professor of the Practice of Computer Science at <a href="https://www.harvard.edu/">Harvard University</a> in the <a href="https://www.seas.harvard.edu/">School of Engineering and Applied Sciences</a>, a Member of the Faculty of Education in the <a href="https://www.gse.harvard.edu/">Graduate School of Education</a>, and the Faculty Director of the Educational Innovation Laboratory at the <a href="https://dce.harvard.edu/">Harvard Division of Continuing Education</a>. He teaches Computer Science 50, otherwise known as CS50, which is among Harvard University’s largest courses, one of Yale University’s largest courses, and edX’s largest MOOC, with more than 6.2M registrants. He also teaches at <a href="https://hls.harvard.edu/">Harvard Law School</a>, <a href="https://www.extension.harvard.edu/">Harvard Extension School</a>, and <a href="https://www.summer.harvard.edu/">Harvard Summer School</a> and has also taught at <a href="https://www.hbs.edu/">Harvard Business School</a>. All of his courses are freely available as OpenCourseWare, with more than 2M subscribers on YouTube.</p>

<p>Malan also operates the <a href="https://regenttheatre.com/">Regent Theatre</a>, a 450-seat historic theatre in Arlington, Massachusetts, built in 1916 as a vaudeville house, now a performing arts space operating as a public benefit company, its mission “positive effects of artistic, charitable, cultural, educational, or technological nature through operation of community theatre and production of high-quality content.”</p>

<p class="fw-bold">Degrees</p>
<ul class="fa-ul">
<li>
<span class="fa-li fas fa-graduation-cap"></span>
<div>Ph.D., Computer Science, 2007</div>
<div class="small">Harvard University</div>
</li>
<li>
<span class="fa-li fas fa-graduation-cap"></span>
<div>S.M., Computer Science, 2004</div>
<div class="small">Harvard University</div>
</li>
<li>
<span class="fa-li fas fa-graduation-cap"></span>
<div>A.B., Computer Science, 1999</div>
<div class="small">Harvard University</div>
</li>
</ul>

<p class="fw-bold">Honorary Degree</p>
<ul class="fa-ul">
<li>
<span class="fa-li fas fa-graduation-cap"></span>
<div>Honorary Doctorate (Dr. h. c), 2022</div>
<div class="small">Faculty of Management &amp; Technology, Leuphana University Lüneburg</div>
</li>
</ul>

<p class="fw-bold">Interests</p>
<ul>
<li>artificial intelligence</li>
<li>collaborative learning</li>
<li>computer-assisted instruction</li>
<li>cybersecurity</li>
<li>computer science education</li>
<li>distance learning</li>
</ul>

                </main>
            </div>

        </div>

        <script>

            // https://getbootstrap.com/docs/5.3/customize/color-modes/#javascript

            /*!
             * Color mode toggler for Bootstrap's docs (https://getbootstrap.com/)
             * Copyright 2011-2022 The Bootstrap Authors
             * Licensed under the Creative Commons Attribution 3.0 Unported License.
             */

            (() => {
              'use strict'

              const storedTheme = localStorage.getItem('theme')

              const getPreferredTheme = () => {
                if (storedTheme) {
                  return storedTheme
                }

                return window.matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light'
              }

              const setTheme = function (theme) {
                if (theme === 'auto' && window.matchMedia('(prefers-color-scheme: dark)').matches) {
                  document.documentElement.setAttribute('data-bs-theme', 'dark')
                } else {
                  document.documentElement.setAttribute('data-bs-theme', theme)
                }
              }

              setTheme(getPreferredTheme())

              const showActiveTheme = theme => {
                const activeThemeIcon = document.querySelector('.theme-icon-active use')
                const btnToActive = document.querySelector(`[data-bs-theme-value="${theme}"]`)
                const svgOfActiveBtn = btnToActive.querySelector('svg use').getAttribute('href')

                document.querySelectorAll('[data-bs-theme-value]').forEach(element => {
                  element.classList.remove('active')
                })

                btnToActive.classList.add('active')
                activeThemeIcon.setAttribute('href', svgOfActiveBtn)
              }

              window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', () => {
                if (storedTheme !== 'light' || storedTheme !== 'dark') {
                  setTheme(getPreferredTheme())
                }
              })

              window.addEventListener('DOMContentLoaded', () => {
                showActiveTheme(getPreferredTheme())

                document.querySelectorAll('[data-bs-theme-value]')
                  .forEach(toggle => {
                    toggle.addEventListener('click', () => {
                      const theme = toggle.getAttribute('data-bs-theme-value')
                      localStorage.setItem('theme', theme)
                      setTheme(theme)
                      showActiveTheme(theme)
                    })
                  })
              })
            })()

        </script>

    


<div id="voila-extension-app" data-v-app=""><div class="Voila_Extension" data-v-49ecc224=""><!----><!----></div></div></body></html>
