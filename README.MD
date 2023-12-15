<div align="center">
<img src="https://media.licdn.com/dms/image/D4D16AQHsR1VL96G2ew/profile-displaybackgroundimage-shrink_350_1400/0/1699772699852?e=1707955200&v=beta&t=vVbNYBBh_bv3t16lzkbD65S_ngBstpvwh1dlt4WbCEc" alt="Description of the image">
# शिवताण्डवस्तोत्रम्

**जटाटवीगलज्जलप्रवाहपावितस्थले**  
**गलेऽवलम्ब्य लम्बितां भुजङ्गतुङ्गमालिकाम्।**  
**डमड्डमड्डमड्डमन्निनादवड्डमर्वयं**  
**चकार चण्डताण्डवं तनोतु नः शिवः शिवम्॥**

</div>


    <>
      <section>
        <div className="max-w-5xl px-8 py-24 pb-12 mx-auto 2xl:max-w-7xl md:px-lg:px-24 lg:pt-32">
          <div className="flex items-center">
            <div>
              <img className="inline-block object-cover w-24 h-48 rounded-full lg:w-64 lg:h-96" src="./Profile.jpg" alt="" />
            </div>
            <div className="ml-4 md:ml-8">
              <p className="text-4xl font-semibold tracking-tighter text-gray-900 md:text-6xl lg:text-7xl">
                {
                  config.profile.name
                }
                <span className="block text-gray-500">
                  {
                    config.profile.role
                  }
                </span>
              </p>
              <div className="flex mt-12 space-x-6 text-xs text-gray-500 uppercase">
                {
                  config.profile.socialLinks.map((item: any, index: number) => {
                    return (
                      <Link key={index} className="hover:text-gray-900" href={item.url} target="_blank">{item.name}</Link>
                    )
                  })
                }
              </div>
            </div>
          </div>
        </div>
      </section>
      <section>
        <div className="max-w-5xl px-8 py-12 mx-auto 2xl:max-w-7xl md:px-lg:px-24">
          <div className="grid grid-cols-1 gap-4 md:grid-cols-2 lg:grid-cols-3 lg:gap-12">
            <div className="flex flex-col gap-12">
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Contact
                </h2>
                <dl className="mt-4 space-y-4 text-sm text-gray-600">
                  <div className="flex items-center text-sm text-gray-500 gap-x-4">
                    <dt className="flex-none">
                      <span className="sr-only">Website</span><svg xmlns="http://www.w3.org/2000/svg" className="icon icon-tabler icon-tabler-world" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                        <path d="M3 12a9 9 0 1 0 18 0a9 9 0 0 0 -18 0"></path>
                        <path d="M3.6 9h16.8"></path>
                        <path d="M3.6 15h16.8"></path>
                        <path d="M11.5 3a17 17 0 0 0 0 18"></path>
                        <path d="M12.5 3a17 17 0 0 1 0 18"></path>
                      </svg>
                    </dt>
                    <dd>
                      <Link className="hover:text-gray-900" href={
                        config.contact.website
                      } target="_blank">
                        {
                          config.contact.website
                        }
                      </Link>
                    </dd>
                  </div>
                  <div className="flex items-center text-sm text-gray-500 gap-x-4">
                    <dt className="flex-none">
                      <span className="sr-only">Telephone</span><svg xmlns="http://www.w3.org/2000/svg" className="icon icon-tabler icon-tabler-device-mobile" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                        <path d="M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2h-8a2 2 0 0 1 -2 -2v-14z"></path>
                        <path d="M11 4h2"></path>
                        <path d="M12 17v.01"></path>
                      </svg>
                    </dt>
                    <dd>
                      <Link className="hover:text-gray-900" href="tel:+1 (555) 234-5678">
                        {
                          config.contact.telephone
                        }
                      </Link>
                    </dd>
                  </div>
                  <div className="flex items-center text-sm text-gray-500 gap-x-4">
                    <dt className="flex-none">
                      <span className="sr-only">Email</span><svg xmlns="http://www.w3.org/2000/svg" className="icon icon-tabler icon-tabler-mail" width="18" height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                        <path d="M3 7a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2h-14a2 2 0 0 1 -2 -2v-10z"></path>
                        <path d="M3 7l9 6l9 -6"></path>
                      </svg>
                    </dt>
                    <dd>
                      <Link className="hover:text-gray-900" href={config.contact.email}>
                        {
                          config.contact.email
                        }
                      </Link>
                    </dd>
                  </div>
                </dl>
              </div>
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Education
                </h2>
                <dl className="mt-4 space-y-4 text-sm text-gray-600">
                  {
                    config.education.map((item: any, index: number) => {
                      return (
                        <div className="flex flex-col gap-2" key={index}>
                          <dt className="flex flex-col">
                            <span className="block">
                              {
                                item.degree
                              }
                            </span><span className="block">
                              {
                                item.college
                              }
                            </span>
                          </dt>
                          <dd className="font-medium text-blue-500">
                            {
                              item.year
                            }
                          </dd>
                        </div>
                      )
                    }
                    )
                  }
                </dl>
              </div>
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Expertise
                </h2>
                <ul role="list" className="mt-4 space-y-2 text-sm text-gray-600">
                  {
                    config.expertise.map((item: any, index: number) => {
                      return (
                        <li key={index}>
                          {
                            item
                          }
                        </li>
                      )
                    })
                  }
                </ul>
              </div>
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Skills
                </h2>
                <ul role="list" className="mt-4 space-y-2 text-sm text-gray-600">
                  {
                    config.skills.map((item: any, index: number) => {
                      return (
                        <li key={index}>
                          {
                            item
                          }
                        </li>
                      )
                    })
                  }
                </ul>
              </div>
            </div>
            <div className="flex flex-col gap-12 lg:col-span-2">
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">About</h2>
                <p className="mt-4 text-sm text-gray-600">
                  {
                    config.about
                  }
                </p>
              </div>
              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Work experience
                </h2>
                <div className="flex flex-col gap-8">
                  {
                    config.workExperience.map((item: any, index: number) => {
                      return (
                        <div>
                          <Link href={item.link} target='_blank' className="mt-4 text-lg font-medium text-blue-500">
                            {
                              item.company
                            }
                            <span className="text-gray-500">
                              (
                              {
                                item.position
                              }
                              )
                            </span>
                            <span className="block text-xs text-gray-500">
                              {
                                item.year
                              }
                            </span>
                          </Link>
                          <p className="mt-4 text-sm font-medium text-gray-500">
                            {
                              item.description
                            }
                          </p>
                        </div>
                      )
                    })
                  }
                </div>
              </div>

              <div>
                <h2 className="text-2xl font-bold tracking-tight text-gray-900">
                  Projects Done
                </h2>
                <div className="flex flex-col gap-8">
                  {
                    config.projects.map((item: any, index: number) => {
                      return (
                        <div>
                          <Link href={item.link} target='_blank' className="mt-4 text-lg font-medium text-blue-500">
                            {
                              item.projectName
                            }
                            <span className="text-gray-500">
                              {
                                item.techstack
                              }
                            </span>
                            <span className="block text-xs text-gray-500">
                              {
                                item.year
                              }
                            </span>
                          </Link>
                          <p className="mt-4 text-sm font-medium text-gray-500">
                            {
                              item.description
                            }
                          </p>
                        </div>
                      )
                    })
                  }
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <footer>
        <div className="max-w-5xl px-8 py-12 mx-auto 2xl:max-w-7xl md:px-lg:px-24 lg:pt-48">
          <p className="max-w-2xl text-sm text-left text-zinc-500">
            © Rdrudra99. Design:
            <Link href="#_/" className="underline underline-offset-2">Rudra Narayan Boitei</Link>
          </p>
        </div>
      </footer>
    </>

